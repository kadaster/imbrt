# Bijlage: Mutatieprotocol

## Inleiding

Deze bijlage beschrijft wanneer er wijzigingen optreden in de identificatie, de objectBeginTijd en tijdstipRegistratie van geo-objecten in TOP10NL. Het doel van het mutatieprotocol is de echte mutaties aan de objecten om te zetten naar mutatieopdrachten voor het wijzigen van de inhoud van beide databases. Het streven daarbij is om een object zoveel mogelijk zijn unieke identificerende kenmerk, het TOP10\_ID, te laten behouden, zodat gegevens die middels het TOP10\_ID zijn gekoppeld niet verloren gaan. Na het uitvoeren van deze mutatieopdrachten zijn de wijzigingen doorgevoerd in de werk-database van TOP10NL.

Bij het gebruik van het mutatieprotocol worden verschillende regels toegepast. Verderop in deze bijlage worden de regels beschreven die op slechts een deel van de geo-objecten van toepassing zijn. Eerst zullen algemeen geldende regels worden genoemd.

## Algemene regels

De algemeen geldende regels zijn:

- Voor het mutatieprotocol is in de meeste situaties alleen de hoofdgeometrie ('werkelijke geometrie') van een geo-object van belang. Dit is het vlak, of als dit niet bestaat de lijn of het punt. Een eventuele aanvullende geometrie is alleen van belang in het mutatieprotocol wanneer dit het enige van een geo-object is dat verandert.
- Indien een geo-object een nieuwe identificatie krijgt, dan krijgt het ook altijd een objectBeginTijd en een zelfde versieBeginTijd.
- Indien een nieuw geo-object de identificatie overneemt van een oud geo-object (dus als er een nieuwe versie ontstaat), dan krijgt het geo-object een nieuwe versieBeginTijd en wordt de oude versie opgeslagen met een zelfde versieEindTijd.
- Indien een geo-object een objectEindTijd krijgt, dan krijgt het een zelfde versieEindTijd.
- Indien een geo-object een andere objectklasse wordt, dan is er altijd sprake van een nieuw geo-object (met een nieuwe identificatie). In werkelijkheid is het oorspronkelijke object namelijk verdwenen en is er een nieuw object voor in de plaats gekomen.

Tijdens een herziening kan er met objecten in de werkelijkheid sprake zijn van:

- Een nieuw object: het object bestond nog niet (ook niet in een andere vorm).
- Een gewijzigd object: het object bestond al wel, maar er is iets aan veranderd.
- Een verdwenen object: het object bestaat niet meer in de werkelijkheid.
- Een onveranderd object: het object is helemaal hetzelfde gebleven.

In figuur B1.1 is te zien wat er met de geo-objecten in de database kan gebeuren in geval van een nieuw object, een gewijzigd object, een verdwenen object of een onveranderd object. Voor elk van deze situaties wordt beschreven wat er in de database gebeurt.

![Stroomschema voor geo-objecten in het mutatieprotocol, waarin te zien is wat er met de geo-objecten in de database kan gebeuren in geval van een nieuw object, een gewijzigd object, een verdwenen object of een onveranderd object.](images/figuurb1-1.svg "Stroomschema voor geo-objecten in het mutatieprotocol")

_Figuur B1.1: Stroomschema voor geo-objecten in het mutatieprotocol._

**Onveranderd object**

Is er in de werkelijkheid niets gebeurt met een object, dan gebeurt er ook niets met de geo-objecten in de database.

**Nieuw object**

Indien een object geheel nieuw is, dan wordt een nieuw geo-object geplaatst in de database. Dat betekent dat het geo-object een nieuwe identificatie krijgt met een objectBeginTijd en een zelfde tijdstipRegistratie.

**Verdwenen object**

Met een verdwenen object wordt niets gedaan in het protocol. De database bevat immers alleen actuele objecten.

**Gewijzigd object**

Als een object wijzigt, dan is de wijziging in de database afhankelijk van de grootte van de wijziging van het geo-object.

- Bij 'kleine' wijzigingen krijgt een geo-object een nieuwe tijdstipRegistratie.
- Bij 'grote' wijzigingen wordt het oorspronkelijke geo-object als een verdwenen object beschouwd en het veranderde geo-object als nieuw object. Het veranderde geo-object krijgt een nieuwe identificatie met een objectBeginTijd en een zelfde tijdstipRegistratie.

Of een wijziging 'klein' of 'groot' is, is subjectief. Daarom zijn er regels opgesteld, waarmee kan worden vastgesteld wat de gevolgen zijn van de wijziging.

Is er een wijziging, dan kan er sprake zijn van een wijziging van attribuutwaarden, van geometrie type of van coördinaten. Een wijziging van coördinaten kan zowel plaatsvinden in de hoofdgeometrie als in de aanvullende geometrie. Afhankelijk van de soort wijziging gelden er bepaalde regels.

### Wijziging van attribuutwaarde

Wat er in de database gebeurt, is afhankelijk van de objectklasse en het attribuut dat van waarde verandert. In de meeste gevallen leidt een wijziging in attribuutwaarde alleen tot een nieuwe versie. Maar bij de verandering van de attributen in tabel B1.1 krijgt het geo-object een nieuwe identificatie. Een wijziging van attribuut hoogteniveau leidt altijd tot een nieuwe identificatie.

| objectklasse | attribuut |
|:---|:---|
| Inrichtingselement | type inrichtingselement |
| Reliëf | type reliëf |
| Hoogte | type hoogte |
| Registratief gebied | type registratief gebied |
| Geografisch gebied | type geografisch gebied |
| Functioneel gebied | type functioneel gebied |
| Plaats | type gebied |
| Plantopografie | type object |

_Tabel B1.1: Attributen die bij wijziging van waarde leiden tot nieuwe identificatie._

### Wijziging van geometrie type of coördinaten van de hoofdgeometrie

Een wijziging in coördinaten is een wijzigingen van de vorm van de geometrie zonder dat het geometrietype verandert.

Het geometrie type is de vorm waarin een geo-object wordt opgeslagen: als punt, lijn of vlak. Door verandering van bijvoorbeeld de breedte van een object kan het geo-object veranderen van een lijn in een vlak. Een wijziging van geometrietype is altijd een wijziging van coördinaten.

Op elk geo-object met deze wijziging wordt de overlapregel toegepast. Indien het 'nieuwe' geo-object na toepassing van deze regel meerdere identificaties krijgt toegewezen, dan wordt de samenvoegregel toegepast.

![Stroomschema voor de overlapregel en de samenvoegregel.](images/figuurb1-2.svg "Stroomschema voor de overlapregel en de samenvoegregel")

_Figuur B1.2: Stroomschema voor de overlapregel en de samenvoegregel._

Nadat alle gewijzigde geo-objecten op deze manier zijn behandeld, wordt er gecontroleerd of een identificatie aan meerdere geo-objecten is toegekend. Indien dit het geval is, dan wordt op deze geo-objecten de splitsregel toegepast.

![Stroomschema voor de splitsregel.](images/figuurb1-3.svg "Stroomschema voor de splitsregel")

_Figuur B1.3: Stroomschema voor de splitsregel._

De verschillende regels worden hieronder beschreven. Bij deze regels is de oppervlakte van de verschillende geo-objecten belangrijk. Om bij puntvormige en lijnvormige geo-objecten ook een oppervlakte te krijgen, wordt er om deze geo-objecten een buffer gelegd (zie figuur B1.4). Indien er in de regels wordt gesproken over de oppervlakte van een geo-object, dan geldt voor punt- en lijnvormige geo-objecten dat de oppervlakte van de buffer bedoeld wordt. Deze geo-objecten kunnen dan net als vlakvormige geo-objecten worden behandeld.

De bufferbreedte is 3 meter en wordt gemeten van de lijn of het punt tot de buitenkant van de buffer. De totale breedte van de buffer is dus 6 meter. Er wordt gebruik gemaakt van een 'vierkante' buffer met afgekapt uiteinde.

![Schematische weergave waarin puntvormige en lijnvormige geo-objecten van een buffer zijn voorzien.](images/figuurb1-4.png "Toepassing van buffers (lichtblauw) om puntvormige en lijnvormige geo-objecten")

_Figuur B1.4: Toepassing van buffers (lichtblauw) om puntvormige en lijnvormige geo-objecten._

#### Overlapregel

Deze regel wordt voor elk 'nieuw' geo-object toegepast. Een 'nieuw' geo-object neemt de identificatie over van een 'oud' geo-object van dezelfde objectklasse en met hetzelfde hoogteniveau, als de oppervlakte van het overlappende gedeelte meer dan de helft is van de oppervlakte van het oorspronkelijke geo-object of van de oppervlakte van het nieuwe geo-object (zie figuur B1.5).

![Schematische weergave van twee geo-objecten die worden samengevoegd. In de oorspronkelijke situatie zijn er twee geo-objecten, met de identificaties 1011 en 1012. In de nieuwe situatie is er nog slechts één geo-object dat gedeeltelijk overlapt met elk van de oorspronkelijke geo-objecten.](images/figuurb1-5.png "Toepassing van de overlapregel")

| identificatie | objectBeginTijd | tijdstipRegistratie |
|:---|:---|:---|
| 1011 | 01-01-2005 | 01-01-2005 |
| 1012 | 01-01-2005 | 01-01-2005 |
| _1012_ | _01-01-2005_ | _01-01-2006_ |

_Figuur B1.5: Toepassing van de overlapregel. De cursieve tekst geeft de nieuwe attribuutwaarden t.o.v. de oorspronkelijke situatie._

In figuur B1.5 worden twee geo-objecten die ontstaan zijn op 01-01-2005 samengevoegd op de datum 01-01-2006. In de oorspronkelijke situatie zijn er twee geo-objecten, met de identificaties 1011 en 1012. In de nieuwe situatie is er nog slechts één geo-object dat overlapt met elk van de oorspronkelijke geo-objecten.

De oppervlakte van het overlappende gedeelte van het nieuwe geo-object met het linker oorspronkelijke geo-object (1011) is minder dan de helft van zowel de oppervlakte van het oorspronkelijke geo-object, als de oppervlakte van het nieuwe geo-object. Het nieuwe geo-object neemt identificatie 1011 niet over. Het geo-object met identificatie 1011 krijgt een versieEindTijd en een objectEindTijd want er is geen ander geo-object dat de identificatie kan overnemen. De oppervlakte van het overlappende gedeelte van het rechter oorspronkelijke geo-object (1012) met het nieuwe geo-object is minder dan de helft van de oppervlakte van het nieuwe geo-object, maar meer dan de helft van de oppervlakte van het oorspronkelijke geo-object. Het nieuwe geo-object neemt identificatie 1012 over en krijgt een nieuwe versieBeginTijd. De vorige versie van dit geo-object krijgt een zelfde tijdstipRegistratie.

#### Samenvoegregel

Als na toepassing van de overlapregel een 'nieuw' geo-object meerdere identificaties krijgt toegewezen, dan wordt de **samenvoeg**regel gebruikt. Deze regel wordt gebruikt wanneer een nieuw geo-object de samenvoeging is van meerdere oorspronkelijke geo-objecten. Het bepaalt van welk oorspronkelijke geo-object de identificatie mag worden overgenomen.

Als de oppervlakte van het nieuwe geo-object minder dan 200% is van de oppervlakte van één van de oorspronkelijke geo-objecten, dan neemt het zijn identificatie over met een nieuwe tijdstipRegistratie. Als de oppervlakte van een nieuw geo-object 200% of meer is, vergeleken met het oorspronkelijke geo-object, dan neemt het niet de identificatie over (zie figuur B1.6).

![Schematische weergave van twee geo-objecten die worden samengevoegd. In de oorspronkelijke situatie zijn er twee geo-objecten, met de identificaties 0011 en 0012. In de nieuwe situatie is er nog slechts één geo-object dat volledig overlapt met elk van de oorspronkelijke geo-objecten.](images/figuurb1-6.png "Toepassing van de samenvoegregel")

| identificatie | objectBeginTijd | versieBeginTijd |
|:---|:---|:---|
| 0011 | 01-01-2005 | 01-01-2005 |
| 0012 | 01-01-2005 | 01-01-2005 |
| _0012_ | _01-01-2005_ | _01-01-2006_ |

_Figuur B1.6: Toepassing van de samenvoegregel. De cursieve tekst geeft de nieuwe attribuutwaarden t.o.v. de oorspronkelijke situatie._

Volgens de overlapregel mag het nieuwe geo-object in figuur B1.6 de identificatie van beide geo-objecten overnemen dus wordt de samenvoegregel toegepast.

De oppervlakte van het nieuwe geo-object is meer dan 200% van de oppervlakte van het oorspronkelijke geo-object met identificatie 0011. Deze identificatie neemt het dus niet over.

De oppervlakte is echter minder dan 200% van de oppervlakte van het oorspronkelijke geo-object met identificatie 0012, dus deze identificatie neemt het wel over. De nieuwe versie van het geo-object krijgt een nieuwe tijdstipRegistratie.

Soms kan, na toepassing van de samenvoegregel, een geo-object toch nog meerdere identificaties overnemen. In dit geval neemt het geo-object geen enkele identificatie over, maar krijgt het een nieuwe identificatie (zie figuur B1.7).

![Schematische weergave van twee geo-objecten die worden samengevoegd. In de oorspronkelijke situatie zijn er twee geo-objecten, met de identificaties 0031 en 0032. In de nieuwe situatie is er nog slechts één geo-object dat volledig overlapt met elk van de oorspronkelijke geo-objecten.](images/figuurb1-7.png "Uitzonderingssituatie na het toepassen van de overlapregel en de samenvoegregel")

| identificatie | objectBeginTijd | versieBeginTijd |
|:---|:---|:---|
| 0031 | 01-01-2005 | 01-01-2005 |
| 0032 | 01-01-2005 | 01-01-2005 |
| _0033_ | _01-01-2006_ | _01-01-2006_ |

_Figuur B1.7: Uitzonderingssituatie na het toepassen van de overlapregel en de samenvoegregel. De cursieve tekst geeft de nieuwe attribuutwaarden t.o.v. de oorspronkelijke situatie._

Na het toepassen van de overlapregel kan het nieuwe geo-object in figuur B1.7 beide oorspronkelijke identificaties (0031 en 0032) overnemen. Dus moet de samenvoegregel worden toegepast. Na het toepassen hiervan kan het nieuwe geo-object nog steeds beide identificaties overnemen. Dit kan niet, dus krijgt het een nieuwe identificatie (0033) met een nieuwe objectBeginTijd en een zelfde tijdstipRegistratie.

#### Splitsregel

Nadat alle 'nieuwe' geo-objecten de overlapregel en eventueel de samenvoegregel hebben doorlopen, wordt er gecontroleerd of er identificaties zijn die aan meerdere geo-objecten zijn toegekend. Dit kan gebeuren als een oorspronkelijk geo-object is opgedeeld in meerdere nieuwe geo-objecten. In die gevallen wordt de splitsregel toegepast.

Is de oppervlakte van een nieuw geo-object meer dan 50% van de oppervlakte van het oorspronkelijke geo-object, dan neemt het zijn identificatie over met een nieuwe tijdstipRegistratie. De andere nieuw gevormde geo-objecten krijgen een nieuwe identificatie met een nieuwe objectBeginTijd en een zelfde tijdstipRegistratie (zie figuur B1.86).

![Schematische weergave van een geo-object dat wordt gesplitst. In de oorspronkelijke situatie is er één geo-object, met de identificatie 0001. In de nieuwe situatie zijn er twee geo-objecten die samen het oude object afdekken.](images/figuurb1-8.png "Toepassing van de splitsregel")

| identificatie | objectBeginTijd | versieBeginTijd |
|:---|:---|:---|
| 0001 | 01-01-2005 | 01-01-2005 |
| _0002_ | _01-01-2006_ | _01-01-2006_ |
| _0001_ | _01-01-2005_ | _01-01-2006_ |

_Figuur B1.8: Toepassing van de splitsregel. De cursieve tekst geeft de nieuwe attribuutwaarden t.o.v. de oorspronkelijke situatie._

Na het toepassen van de overlapregel op beide 'nieuwe' geo-objecten blijken ze beide de identificatie 0001 te mogen krijgen. Dit mag niet en de splitsregel wordt toegepast.

De oppervlakte van het kleine nieuwe geo-object in figuur B1.8 is minder dan 50% van de oppervlakte van het oorspronkelijke geo-object. Het neemt de identificatie niet over en krijgt een nieuwe identificatie met een nieuwe objectBeginTijd en tijdstipRegistratie. De oppervlakte van het grote nieuwe geo-object is meer dan 50% van de oppervlakte van het oorspronkelijke geo-object en neemt de identificatie 0001 wel over, uiteraard met een nieuwe tijdstipRegistratie.

Soms kunnen, na toepassing van deze regel, toch meerdere geo-objecten de identificatie van het oorspronkelijke geo-object overnemen. In dit geval neemt geen enkel geo-object de identificatie over, maar krijgen ze allemaal een nieuwe identificatie met een nieuwe objectBeginTijd en een zelfde tijdstipRegistratie (zie figuur B1.9).

![Schematische weergave van een geo-object dat wordt gesplitst. In de oorspronkelijke situatie is er één geo-object, met de identificatie 0021. In de nieuwe situatie zijn er twee geo-objecten die samen het oude object afdekken.](images/figuurb1-9.png "Uitzonderingssituatie na het toepassen van de overlapregel en de splitsregel")

| identificatie | objectBeginTijd | versieBeginTijd |
|:---|:---|:---|
| 0021 | 01-01-2005 | 01-01-2005 |
| _0022_ | _01-01-2006_ | _01-01-2006_ |
| _0023_ | _01-01-2006_ | _01-01-2006_ |

_Figuur B1.9: Voorbeeld waarbij overlapregel en splitsregels nog geen uitsluitsel geven. De cursieve tekst geeft de nieuwe attribuutwaarden t.o.v. de oorspronkelijke situatie._

Na het toepassen van de overlapregel in figuur B1.9 kunnen beide geo-objecten de identificatiecode 0021 overnemen. Dit is nog steeds het geval na het toepassen van de splitsregel, dus krijgen beide nieuwe geo-objecten een nieuwe identificatie (0022 en 0023).

### Wijziging van coördinaten van de aanvullende geometrie

Indien de enige wijziging van een geo-object een wijziging van de coördinaten van de aanvullende geometrie is, dan komt er een nieuwe versie van het geo-object waarbij deze een zelfde tijdstipRegistratie krijgt. Indien er ook andere wijzigingen plaatsvinden, dan wordt de aanvullende geometrie, en de eventuele veranderingen daarvan, buiten beschouwing gelaten.

## Schema

In onderstaand schema wordt aangegeven wat er in welke situatie gebeurt. Dit is afhankelijk van:

- de objectklasse;
- de verandering (van attribuutwaarde, coördinaten of geometrietype).

| Objectklasse | Verandering van attribuutwaarde | Verandering van coördinaten | Verandering van geometrietype |
|:---|:---|:---|:---|
| Wegdeel | 1 | 3 | 3 | |
| Spoorbaandeel | 1 | 3 | 3 |
| Waterdeel | 1 | 3 | 3 |
| Gebouw | 1 | 3 | 3 |
| Terrein | 1 | 3 | n.v.t. |
| Inrichtingselement | 2 | 3 | 3 |
| Reliëf | 2 | 3 | 4 |
| Hoogte | 2 | 3 | 4 |
| Registratief gebied | 2 | 3 | n.v.t |
| Geografisch gebied | 2 | 3 | 1 |
| Plaats | 2 | 3 | 3 |
| Functioneel gebied | 2 | 3 | 1 |
| Plantopografie | 2 | 3 | 4 |

_Tabel B1.2: Schema gebeurtenis mutatieprotocol._

Verklaring van de nummers:

1\. Het geo-object krijgt een nieuwe tijdstipRegistratie.

2\. Het geo-object krijgt een nieuwe identificatie met een nieuwe objectBeginTijd en een zelfde tijdstipRegistratie als de waarde van het attribuut 'type inrichtingselement', 'type reliëf', 'type hoogte', 'type registratief gebied', 'type geografisch gebied', type gebied', 'type functioneel gebied' gebied' of 'type object' verandert. Het oorspronkelijke geo-object krijgt een objectEindTijd en versieEindTijd.

Indien de waarde van een ander attribuut verandert, dan krijgt het geo-object krijgt een nieuwe tijdstipRegistratie.

3\. Als er alleen coördinaten van _**aanvullende**_ geometrie (b.v. hartlijn) veranderen, dan krijgt het geo-object een nieuwe tijdstipRegistratie.

In alle andere gevallen wordt de overlapregel toegepast. Als een geo-object meerdere identificaties krijgt toegewezen, dan wordt de **samenvoeg**regel gebruikt. Indien na behandeling van alle geo-objecten blijkt dat een identificatie aan meerdere geo-objecten is toegekend, dan wordt de **splits**regel toegepast.

Puntvormige en lijnvormige geo-objecten worden van een buffer van drie meter voorzien om de overlapregel, de splitsregel en de samenvoegregel toe te kunnen passen. Dan wordt de oppervlakte van het geo-object met buffer gebruikt.

Als een nieuw geo-object geen identificatie kan overnemen, dan krijgt het een nieuwe identificatie met een objectBeginTijd en een zelfde tijdstipRegistratie.

4\. Als het geometrietype verandert, dan verandert vaak ook de waarde van het attribuut 'type inrichtingselement', 'type reliëf', 'type hoogte' of 'type object'. Dit heeft al een nieuwe identificatie tot gevolg, dus deze wijziging kan verder buiten beschouwing worden gelaten.
