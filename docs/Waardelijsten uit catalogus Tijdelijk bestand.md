### 7.1.2 Domeinen

#### Domein "Brontype"
| Domein | Brontype |
|:---|:---|
| Domeinwaarde | **TOP10vector** |
| Definitie | Digitaal bestand, bestaande uit gecodeerde vectoren, die tezamen de topografie van Nederland weergeven op de schaal 1:10.000. Voorloper van TOP10NL. |

| Domein | Brontype |
|:---|:---|
| Domeinwaarde | **luchtfoto** |
| Definitie | Een fotografische opname van een deel van het aardoppervlak, gemaakt vanuit een vliegtuig. |

| Domein | Brontype |
|:---|:---|
| Domeinwaarde | **RD** |
| Definitie | Net van vaste punten in Nederland. Deze vaste punten zijn de referentiepunten waarnaar overige metingen en karteringen kunnen verwijzen. De referentiepunten maken deel uit van een netwerk dat is vastgelegd in het systeem van de Rijksdriehoeksmeting (RD). Dit netwerk wordt beheerd en onderhouden door het Kadaster. ( [www.kadaster.nl](https://www.kadaster.nl) ). |

| Domein | Brontype |
|:---|:---|
| Domeinwaarde | **overig** |
| Definitie | De waarde van het objectkenmerk is bekend, maar anders dan de genoemde waarden. |

| Domein | Brontype |
|:---|:---|
| Domeinwaarde | **externe data** |
| Definitie | De data worden aangeleverd door externe leveranciers. |

#### Domein "Mutatietype"

| Domein | Mutatietype |
|:---|:---|
| Domeinwaarde | **kwaliteitsverbetering** |
| Definitie | Aanpassing van het object als gevolg van een kwaliteitsactie. |

| Domein | Mutatietype |
|:---|:---|
| Domeinwaarde | **werkelijke verandering** |
| Definitie | Aanpassing van het object als gevolg van wijzigingen van het object in het terrein. |

| Domein | Mutatietype |
|:---|:---|
| Domeinwaarde | **modelwijziging** |
| Definitie | Aanpassing van het object als gevolg van wijzigingen in het datamodel. |

| Domein | Mutatietype |
|:---|:---|
| Domeinwaarde | **andere bron** |
| Definitie | Aanpassing van het object als gevolg van gebruik van andere bronnen. |

#### Domein "Status"

| Domein | Status |
|:---|:---|
| Domeinwaarde | **in uitvoering** |
| Definitie | Het object is in aanleg. |

| Domein | Status |
|:---|:---|
| Domeinwaarde | **in gebruik** |
| Definitie | Het object wordt gebruikt. |

| Domein | Status |
|:---|:---|
| Domeinwaarde | **buiten gebruik** |
| Definitie | Het object wordt niet meer (als zodanig) gebruikt. |


## 7.13 Objectklasse: functioneel gebied

_Definitie:_

Begrensd en benoemd gebied dat door een functionele eenheid beschreven wordt.

_Inwinningscriteria:_

\-

### Attribuut labelPunt

| Attribuut | labelPunt |
|:---|:---|
| Definitie | De puntgeometrie van een functioneel gebied object. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Point |
| Domein | "Ruimtelijke coördinaten" |

### Attribuut geometrieVlak

| Attribuut | geometrieVlak |
|:---|:---|
| Definitie | De vlakgeometrie van een functioneel gebied object. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Surface of GM\_MultiSurface |
| Domein | "Ruimtelijke coördinaten" |

### Attribuut type functioneel gebied

| Attribuut | type functioneel gebied |
|:---|:---|
| Definitie | Het soort functioneel gebied. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "FG\_typeFunctioneelGebied" |

#### Domein "FG\_typeFunctioneelGebied"

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **attractiepark** |
| Definitie | Park ingericht voor vrijetijdsbesteding. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **bedrijventerrein** |
| Definitie | Het geheel aan gebouwen en terreinen ten behoeve van bedrijven en industrie, inclusief toevoerwegen, tussengelegen water, etc.. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **begraafplaats** |
| Definitie | Het geheel aan voorzieningen t.b.v. het begraven van overledenen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **boswachterij** |
| Definitie | Deel van een houtvesterij onder een boswachter. |
| Inwinningscriteria | Wordt niet ingewonnen. |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **botanische tuin** |
| Definitie | Tuin met verschillende soorten planten en / of bomen voor wetenschappelijke, educatieve of kunstzinnige doeleinden. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **bungalowpark** |
| Definitie | Oppervlak bebouwd met (luxe) vakantiehuisjes. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **camping, kampeerterrein** |
| Definitie | Terrein met voorzieningen t.b.v. verblijfsrecreatie voornamelijk voor tenten, caravans en campers. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **campus** |
| Definitie | Een universiteitsterrein waarop gebouwen en voorzieningen voor zowel docenten als studenten aanwezig zijn. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **caravanpark** |
| Definitie | Terrein met voorzieningen t.b.v. verblijfsrecreatie voornamelijk ingericht met stacaravans. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **circuit** |
| Definitie | Verhard terrein voor snelheidswedstrijden. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **crossbaan** |
| Definitie | Onverhard terrein voor snelheidswedstrijden en hiervoor uitgerust met de nodige voorzieningen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **dierentuin, safaripark** |
| Definitie | Publieke tuin / park waarin een verzameling inheemse en uitheemse dieren is ondergebracht (dierentuin).<br>Groot park met wilde dieren, waar men met een auto doorheen kan rijden (safaripark). |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **eendenkooi** |
| Definitie | Stuk land en water met een karakteristieke vorm, ingericht om wilde eenden te vangen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **emplacement** |
| Definitie | Het totaal aan sporen op een terrein ten behoeve van het rangeren en stallen van treinen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **erebegraafplaats** |
| Definitie | Begraafplaats voor gesneuvelde militairen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **gaswinning** |
| Definitie | Gebied met installatie(s) t.b.v. de winning of transport van aardgas. |
| Inwinningscriteria | Minimumgrootte: 1000 m². Indien kleiner, dan wordt het opgenomen als inrichtingselement. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **gebied met hoge objecten** |
| Definitie | Gebied, waarbinnen zich meerdere hoge objecten bevinden. |
| Inwinningscriteria | Wordt niet ingewonnen. |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **gebied voor radioastronomie** |
| Definitie | Gebied waarin sensoren opgesteld zijn ten behoeven van radio-astronomie. |
| Inwinningscriteria | Beperkt |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **gebouwencomplex** |
| Definitie | Geheel van bij elkaar horende gebouwen. |
| Inwinningscriteria | Bijvoorbeeld universiteit of veiling. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **golfterrein** |
| Definitie | Terrein toegerust voor de uitoefening van de golfsport. |
| Inwinningscriteria | Ook de kleinschalige variant Pitch en Putt wordt ingewonnen als golfterrein. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **grafheuvel** |
| Definitie | Voorhistorische begraafplaats in de vorm van een heuvel. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **grindwinning** |
| Definitie | Gebied waar winning van grind plaatsvindt (in dagbouw of d.m.v. zuigen). |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **groeve** |
| Definitie | Opengegraven ruimte waaruit een delfstof gewonnen wordt. |
| Inwinningscriteria | Bijvoorbeeld mergelgroeve of zandgroeve. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **haven** |
| Definitie | Lig- en bergplaats voor vaartuigen, inclusief het omliggende terrein. |
| Inwinningscriteria | Ook vluchthavens en werkhavens met omliggend terrein worden aangegeven. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **heemtuin** |
| Definitie | Tuin waar de inheemse flora en fauna ter instructie te bezichtigen zijn. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **helikopterlandingsterrein** |
| Definitie | Terrein dat als landings- en vertrekplaats dient voor helikopters. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **ijsbaan** |
| Definitie | Terrein dat in de winter onder water wordt gezet om te dienen als schaatsgelegenheid of dat is voorzien van een installatie waarmee een ijsvloer kan worden gelegd. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **infiltratiegebied** |
| Definitie | Gebied waar water wordt gezuiverd door infiltratie t.b.v. de drinkwatervoorziening. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **jachthaven** |
| Definitie | Lig- en bergplaats voor pleziervaartuigen, tezamen met het omliggende terrein. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **kartingbaan** |
| Definitie | Baan waarop met skelters of karts gereden wordt. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **kassengebied** |
| Definitie | Gebied bestaande uit meerdere landbouwkassen. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **kazerne, legerplaats** |
| Definitie | Gebouw(-encomplex) bestemd tot huisvesting van soldaten. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **landgoed** |
| Definitie | Buitenverblijf met omliggende landerijen. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **mijn** |
| Definitie | Plaats waar ertsen, steenkool, enz. worden gedolven. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **milieustraat** |
| Definitie | Een locatie die specifiek bestemd is voor het brengen van gescheiden huishoudelijk afval en grofvuil. |
| Inwinningscriteria | De in de wijken gelegen milieu-inzamelpunten worden niet gegeven. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **militair oefengebied, schietterrein** |
| Definitie | Militair kamp voor het houden van schietoefeningen met zware vuurwapens (artillerie schietkamp). / Terrein ingericht voor het schieten op doelen (schietkamp). / Terrein waar militairen oefenen (militair oefenterrein). |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **mosselbank** |
| Definitie | Plaats waar mosselen gekweekt worden. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **nationaal park** |
| Definitie | Een door de rijksoverheid aangewezen terrein van nationale landschappelijke betekenis. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **natuurgebied** |
| Definitie | Gebied dat waarde heeft uit een oogpunt van natuurschoon of natuurleven. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **oliewinning** |
| Definitie | Installatie t.b.v. de winning of transport van aardolie. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **openluchtmuseum** |
| Definitie | Historisch museum in de open lucht, waarin de vroegere woon- en werkomgeving van de mens is gereconstrueerd. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **openluchttheater** |
| Definitie | Plaats waar toneelvoorstellingen in de openlucht plaatsvinden. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **park** |
| Definitie | Een op zichzelf staande groenvoorziening, dienend ter verfraaiing en/of verlevendiging van één of meerdere wijken, zonder hiervan direct deel uit te maken. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **plantsoen** |
| Definitie | Kleinschalige groenvoorziening, soms met wandel- en speelmogelijkheden, temidden van bebouwing, ter verfraaiing en verlevendiging van deze bebouwing. |
| Inwinningscriteria | Een plantsoen bestaat niet altijd uit gras en kan soms een andere ondergrond hebben. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **productie-installatie** |
| Definitie | Het geheel van reactorvaten, kolommen, aan- en afvoerpijpen, bebouwing etc. t.b.v. de vervaardiging van chemische producten. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **recreatiegebied** |
| Definitie | Terrein bedoeld voor vrijetijdsbesteding. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **renbaan** |
| Definitie | Het geheel aan gebouwen en installaties bedoeld voor draf- of renwedstrijden. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **skibaan** |
| Definitie | Terrein ingericht voor het beoefenen van de skisport. |
| Inwinningscriteria | Alleen buitenskibanen worden aangegeven als functioneel gebied 'skibaan'.<br>Ook kabelskibanen voor het beoefenen van de waterskisport worden gegeven als functioneel gebied 'skibaan' met soortnaam "Kabelskibaan".<br>Binnenskibanen worden gegeven als gebouw met soortnaam "Skicentrum". |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **slipschool** |
| Definitie | Rijschool waar men een slippend voertuig leert beheersen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **sluizencomplex** |
| Definitie | Het geheel aan voorzieningen, zoals gebouwen, terreinen, etc., behorende tot een sluizencomplex (ook schutsluizen en uitwateringssluizen). |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **sportterrein, sportcomplex** |
| Definitie | Het geheel aan voorzieningen (velden, kleedruimten, groenvoorziening, parkeerterrein, wegen, tribunes, etc.) t.b.v. de beoefening van sport. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **stortplaats** |
| Definitie | Plaats waar afval gestort mag worden. |
| Inwinningscriteria | Het gehele object wordt aangegeven als functioneel gebied van het type stortplaats indien er nog actief wordt gestort. Een afvalbrengstation, milieustraat of stortbordes wordt niet als stortplaats aangegeven. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **tennispark** |
| Definitie | Terrein ingericht voor de beoefening van de tennissport. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **transformatorstation** |
| Definitie | Gebied met installatie(s) voor het transformeren van elektrische stroom. |
| Inwinningscriteria | Wordt alleen ingewonnen indien verbonden met een of meerdere hoogspanningsleidingen. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **tuincentrum** |
| Definitie | Het geheel aan bebouwing en omliggend terrein t.b.v. de (particuliere) verkoop van artikelen voor tuinaanleg. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **vakantiepark** |
| Definitie | Een terrein met voorzieningen t.b.v. verblijfsrecreatie, waarop een combinatie van bungalows en / of stacaravans en / of kampeerplaatsen voorkomt. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **verdedigingswerk** |
| Definitie | Historisch verdedigingswerk, al dan niet voorzien van een of meer (door aarde bedekte) gebouwen of ruïnes. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **verzorgingsplaats** |
| Definitie | Locatie langs een autosnelweg of hoofdweg met een parkeerfunctie, meestal in combinatie met een brandstofverkooppunt en soms aangevuld met een wegrestaurant. |
| Inwinningscriteria | Wordt aangegeven indien gelegen langs een autosnelweg of hoofdweg. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **viskwekerij** |
| Definitie | Terrein met bassins, aangelegd voor het kweken van vis. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **visvijvercomplex** |
| Definitie | Het geheel aan voorzieningen t.b.v. sportvissen. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **vliegveld, luchthaven** |
| Definitie | Vliegveld voor verkeersvliegtuigen met groot, effen terrein met al dan niet verharde banen, waar vliegtuigen kunnen opstijgen en landen, eventueel met accommodatie voor ontvangst en vertrek van passagiers en verzending van goederen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **volkstuinen** |
| Definitie | Het geheel aan voorzieningen t.b.v. hobbytuinbouw. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **waterkering** |
| Definitie | Geheel van een dijk of dam, inclusief talud. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **werf** |
| Definitie | Werkplaats waar schepen worden gebouwd of hersteld. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **wildwissel** |
| Definitie | Civieltechnisch kunstwerk om dieren een veilige oversteek te bieden over of onder een weg. |
| Inwinningscriteria | Wordt niet gegeven indien het slechts een kokervormige buis betreft. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **windturbinepark** |
| Definitie | Concentratie van windturbines. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **woonwagencentrum** |
| Definitie | Plaats waar gewoond wordt in woonwagens. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **zandwinning** |
| Definitie | Gebied waar winning van zand plaatsvindt door middel van zuigen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **zenderpark** |
| Definitie | Gebied waar meerdere zendmasten staan opgesteld. |
| Inwinningscriteria | De zendmasten worden gegeneraliseerd aangegeven. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **ziekenhuiscomplex** |
| Definitie | Het geheel van gebouwen die tezamen een ziekenhuis vormen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **zonnepark** |
| Definitie | Gebied ten behoeve van de opwekking van zonne-energie of zonnewarmte. |
| Inwinningscriteria | Het onderliggende terrein wordt gegeven volgens voorkomen of, indien niet te bepalen, als type 'overig bodemgebruik'. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **zoutwinning** |
| Definitie | Gebied waar zoutwinning plaatsvindt. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **zuiveringsinstallatie** |
| Definitie | Het gebied omvattende het geheel aan voorzieningen t.b.v. de zuivering van afvalwater. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **zweefvliegveldterrein** |
| Definitie | Het geheel aan terreinen, gebouwen enz. voor (de beoefening van) de zweefvliegsport. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **zwembadcomplex** |
| Definitie | Het geheel aan voorzieningen rond een openbaar zwembad. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | FG\_typeFunctioneelGebied |
|:---|:---|
| Domeinwaarde | **overig** |
| Definitie | Het type functioneel gebied is bekend, maar anders dan de genoemde waarden. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut soortnaam

| Attribuut | soortnaam |
|:---|:---|
| Definitie | Verdere specificatie van het type functioneel gebied. |
| Inwinningscriteria | Bijvoorbeeld "bejaardencentrum" in geval van een gebouwencomplex, "mergelgroeve" in het geval van een groeve of "vluchthaven" indien het type functioneel gebied een haven is. |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut naam (Nl)

| Attribuut | naam (Nl) |
|:---|:---|
| Definitie | De Nederlandse naam van het functionele gebied. |
| Inwinningscriteria | In principe worden, indien aanwezig, alleen de geografische namen (toponiemen) van de functionele gebieden worden ingewonnen. |
| Volledigheid | Beperkt |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut naam (Fr)

| Attribuut | naam (Fr) |
|:---|:---|
| Definitie | De Friese naam van het functionele gebied. |
| Inwinningscriteria | Wordt alleen in Friesland ingewonnen. |
| Volledigheid | Beperkt |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

## 7.5 Objectklasse: gebouw

_Definitie:_

Vrijstaande, overdekte en geheel of gedeeltelijk met wanden omsloten toegankelijke ruimte of door pilaren ondersteunde dakconstructie, die direct of indirect met de grond is verbonden.

_Inwinningscriteria:_

- Met ingang van april 2020 is het muteren van gebouwen in de BRT gebaseerd op mutaties in de Basisregistratie Adressen en Gebouwen (BAG). Alle mutaties die in de BAG plaatsvinden worden in enigszins gegeneraliseerde vorm overgenomen in de BRT. Als peildatum voor de BAG-mutaties is hierbij 1 juni gebruikt, omdat dit het beste aansluit bij de luchtfoto’s waarmee de andere elementen in de BRT worden bijgewerkt. Omwille van de actualiteit worden ook BAG-panden met een voorlopige geometrie (status: "bouw gestart" en "pand in gebruik (niet ingemeten)") in dit proces meegenomen. 

- Een gebouw moet een permanent karakter hebben en bedoeld zijn voor verblijf, handel, verkeer en/of arbeid.

- De orthogonale projectie van de uiterste buitenrand inclusief carports en passages (overbouwing van een weg reikend van gebouw tot gebouw, enkel bestaand uit een al dan niet licht doorlatend dak), exclusief luifels, op onderliggend terrein, wegen of water wordt opgenomen. Een stationsoverkapping wordt ingewonnen als gebouw, een overkapping van alleen een perron op een station wordt niet opgenomen. Bebouwing boven (hoge) poorten maakt onderdeel uit van de opgaande bebouwing. Bebouwing, geheel of gedeeltelijk gelegen over een ander object, wordt als bebouwing aangegeven.

- De minimumgrootte voor een gebouwvlak is 9 m².

- Gebouwen, gelegen onder de projectie van andere gebouwen wordt niet opgenomen. Is echter een deel van het gebouw wel zichtbaar dan wordt het gehele gebouw op basis van interpretatie zo goed mogelijk aangegeven waarbij het gebouwdeel gelegen onder het object een hoogteniveau kleiner dan nul krijgt.

- Twee stukken bebouwing worden samengevoegd indien de afstand tussen de orthogonale projecties 2 meter of minder bedraagt, behalve als er tussen de gebouwen een weg of water voorkomt en als de gebouwen in verschillende rijen van bebouwing staan, gezien vanaf de ontsluitingsweg.

- Uitbouwsels tot plm. 3x3 meter en luifels worden verwaarloosd. Inspringingen tot plm. 3x3 meter worden aangegeven als onderdeel van de bebouwing. Een loopgang of loopbrug wordt als onderdeel van het gebouw opgenomen indien deze 3 meter of breder is. Bij openingen groter dan plm. 3 meter wordt het hierdoor ontsloten binnenterrein wel gegeven, waarna een nieuwe afweging gemaakt wordt of er sprake is van een gebouw dan wel een bebouwd oppervlak.

- Een open gedeelte binnen bebouwing (waarbij loopgangen buiten beschouwing worden gelaten), niet direct bereikbaar vanaf de openbare weg, kleiner dan ongeveer 1000 m² wordt niet opgenomen. Deze regel geldt echter niet voor boerderijen met ommuurde binnenplaats zoals deze in Limburg voorkomen.

- Het al dan niet aangegeven van een gebouw is afhankelijk van de omgeving waarin dit gebouw staat. In een gebied met weinig bebouwing wordt elk gebouw aangegeven (vanwege de oriënterende waarde).

- In een gebied met drukke bebouwing worden gebouwen kleiner dan 50 m² achter de eerste rij gebouwen gezien vanaf de ontsluitingsweg niet opgenomen.

- Boothuizen worden als gebouw ingewonnen.

- Op een volkstuincomplex worden de gebouwen gegeneraliseerd weergegeven.

- Een kas wordt aangegeven als een gebouw van het type kas, warenhuis, indien groter dan 200 m².

- Hooibergen worden niet opgenomen. Echter wordt een carport, al dan niet vrijstaand, wel opgenomen.

- Bij een steeg (nauwe straat binnen bebouwd gebied, smaller dan 2 meter) wordt de weg als vlak i.p.v. als lijn ingewonnen en worden de gebouwen vertekend opgenomen.

- De torens van een stormvloedkering worden als gebouw ingewonnen.

- Een tribune die een geheel vormt met de bebouwing wordt als gebouw ingewonnen.

- Voor bestaande bebouwing gelden, in tegenstelling tot nieuw in te winnen gebouwen, afwijkende inwinregels. Kleinere mutaties in de vorm van het gebouw, zoals een aanbouw of carport, worden bij de actualisering genegeerd. Deze regel is geïntroduceerd vanwege het gebruik van de TOP10NL gebouwen door het CBS en nu nog actief vanwege de komst van de BAG als bron voor de gebouwen in TOP10NL.

- Drijvende bebouwing met het voorkomen van een huis en met een permanente (flexibele) verankering (waterwoning) wordt aangegeven als normale bebouwing. Het onderliggende waterdeel wordt overkluisd gegeven. Woonboten worden, ongeacht de verschijningsvorm, niet aangegeven.

- Loopstallen ten behoeve van stalling van rundvee (ook wel ligboxenstal genoemd), zowel voorkomend met een open als een gesloten (dak)constructie worden als gebouw ingewonnen.

### Attribuut geometriePunt

| Attribuut | geometriePunt |
|:---|:---|
| Definitie | De puntgeometrie van een gebouw object. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Point |
| Domein | "Ruimtelijke coördinaten" |

### Attribuut geometrieVlak

| Attribuut | geometrieVlak |
|:---|:---|
| Definitie | De vlakgeometrie van een gebouw object. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Surface |
| Domein | "Ruimtelijke coördinaten" |

### Attribuut fysiek voorkomen

| Attribuut | fysiek voorkomen |
|:---|:---|
| Definitie | De plaats waar het object zich bevindt t.o.v. andere constructies. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Domein | "GB\_fysiekVoorkomen" |

#### Domein "GB\_fysiekVoorkomen"

| Domein | GB\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **ondergronds** |
| Definitie | Gebouw gelegen onder het maaiveld. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | GB\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **overkluisd** |
| Definitie | Gebouw overbouwd door andere bebouwing. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut gebruiksdoel

| Attribuut | gebruiksdoel |
|:---|:---|
| Definitie | Huidig gebruiksdoel van een gebouw, conform de BAG classificatie voor panden |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | **"GE\_gebruiksdoel"** |

#### Domein GE\_gebruiksdoel

| Domein | **GE\_gebruiksdoel** |
|:---|:---|
| Domeinwaarde | **bijeenkomstfunctie** |
| Definitie | Gebouw waar bijeenkomsten voor personen kunnen worden georganiseerd. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | **GE\_gebruiksdoel** |
|:---|:---|
| Domeinwaarde | **celfunctie** |
| Definitie | Gebouw waar personen in bewaring kunnen worden gesteld. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | **GE\_gebruiksdoel** |
|:---|:---|
| Domeinwaarde | **gezondheidszorgfunctie** |
| Definitie | Gebouw waar lichamelijke of geestelijke gezondheidszorg kan worden verleend. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | **GE\_gebruiksdoel** |
|:---|:---|
| Domeinwaarde | **industriefunctie** |
| Definitie | Gebouw waar industriële activiteiten plaatsvinden. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | **GE\_gebruiksdoel** |
|:---|:---|
| Domeinwaarde | **kantoorfunctie** |
| Definitie | Gebouw waar administratieve handelingen plaatsvinden. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | **GE\_gebruiksdoel** |
|:---|:---|
| Domeinwaarde | **logiesfunctie** |
| Definitie | Gebouw waar de mogelijkheid aanwezig is om overnachtingsmogelijkheden aan te bieden. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | **GE\_gebruiksdoel** |
|:---|:---|
| Domeinwaarde | **onderwijsfunctie** |
| Definitie | Gebouw waar onderwijsfaciliteiten worden aangeboden. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | **GE\_gebruiksdoel** |
|:---|:---|
| Domeinwaarde | **sportfunctie** |
| Definitie | Gebouw waar sportieve activiteiten kunnen worden ontplooid. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | **GE\_gebruiksdoel** |
|:---|:---|
| Domeinwaarde | **winkelfunctie** |
| Definitie | Gebouw waar allerhanden roerende of onroerende goederen al dan niet tegen betaling worden aangeboden. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | **GE\_gebruiksdoel** |
|:---|:---|
| Domeinwaarde | **woonfunctie** |
| Definitie | Gebouw geschikt voor permanente bewoning. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | **GE\_gebruiksdoel** |
|:---|:---|
| Domeinwaarde | **overige gebruiksfunctie** |
| Definitie | Indien geen van bovengenoemde functies van toepassing is. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

### Attribuut hoogteniveau

| Attribuut | hoogteniveau |
|:---|:---|
| Definitie | Het hoogteniveau van het object. |
									
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Geheel getal |
| Domein | ≤ 0 (0, -1, -2, -3, …) |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut hoogteklasse

| Attribuut | hoogteklasse |
|:---|:---|
| Definitie | De klasse van hoogte waar de bebouwing toe behoort. |
																					
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
			
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | GE\_hoogteklasse |
							

#### Domein GE\_hoogteklasse

| Domein | GE\_hoogteklasse |
|:---|:---|
| Domeinwaarde | **laagbouw** |
| Definitie | Bebouwing met een hoogte van 35 meter of lager en bestaande uit minder dan 10 woonlagen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GE\_hoogteklasse |
|:---|:---|
| Domeinwaarde | **hoogbouw** |
| Definitie | Gebouwen (als zelfstandige eenheid of onderdeel van een groter gebouw) hoger dan 35 meter of bestaande uit 10 of meer woonlagen. |
| Inwinningscriteria | Een gedeelte **hoogbouw**, wat onderdeel uitmaakt van een groter geheel, wordt als een op zichzelf staand object aangegeven. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

### Attribuut hoogte

| Attribuut | hoogte |
|:---|:---|
| Definitie | De hoogte van het object (t.o.v. het maaiveld of t.o.v. NAP). |
																																	 
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Getal |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut naam

| Attribuut | naam |
|:---|:---|
| Definitie | Naam van het gebouw. |
| Inwinningscriteria | Een bedrijfsnaam wordt niet gegeven. |
| Volledigheid | Beperkt |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut soortnaam

| Attribuut | soortnaam |
|:---|:---|
| Definitie | Nadere specificatie van het type gebouw. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut status

| Attribuut | status |
|:---|:---|
| Definitie | De staat waarin het object zich bevindt. |
																																	 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
			
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "Status" |

### Attribuut type gebouw

| Attribuut | type gebouw |
|:---|:---|
| Definitie | Het type gebouw, het doel waarvoor de bebouwing gebruikt wordt (gaat worden / werd). |
| Inwinningscriteria | Indien de betreffende bebouwing onderdeel uitmaakt van een groter geheel, wordt het gebouwdeel "uitgesneden" uit de omliggende bebouwing en voorzien van de bijbehorende attribuutwaarde. Indien het gebouwdeel niet exact is aan te geven, wordt een op zich zelf staand gebouw aangebracht aan de rand van het complete gebouw (op de ware plek of bij de dichtstbij gelegen ingang van het gebouw). |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "GB\_typeGebouw" |

#### Domein "GB\_typeGebouw"

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **bezoekerscentrum** |
| Definitie | Informatiecentrum in een culturele instelling, een natuurpark, enz.. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **boortoren** |
| Definitie | Tijdelijke of permanente toren voor het verrichten van boorwerkzaamheden. |
| Inwinningscriteria | Indien het object niet voldoet aan de criteria voor een gebouwvlak, dan wordt deze opgenomen als gebouwpunt.<br>Ook een drijvend of op de zeebodem staand platform van waaraf boringen onder water kunnen worden uitgevoerd wordt ingewonnen als boortoren. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **brandtoren** |
| Definitie | Toren t.b.v. het signaleren van een (bos)brand. |
| Inwinningscriteria | Indien het object niet voldoet aan de criteria voor een gebouwvlak, dan wordt deze opgenomen als gebouwpunt. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **brandweerkazerne** |
| Definitie | Gebouw voor het stationeren van materieel en manschappen t.b.v. brandbestrijding. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **bunker** |
| Definitie | Versterkte (schuil)plaats te gebruiken in tijden van oorlog of ramp zowel voor burger- als militaire doeleinden. Kan ook (gedeeltelijk) ondergronds gelegen zijn. |
| Inwinningscriteria | Alleen het bovengrondse gedeelte wordt opgenomen. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **crematorium** |
| Definitie | Gebouw dat dient voor lijkverbranding. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **dok** |
| Definitie | Installatie voor onderhoud en herstel van schepen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **elektriciteitscentrale** |
| Definitie | Gebouw waarin elektriciteit wordt opgewekt. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **fabriek** |
| Definitie | Industriële onderneming waarin op grote schaal stoffen of goederen worden geproduceerd. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **fort** |
| Definitie | Verdedigingswerk. |
| Inwinningscriteria | Van een gedeeltelijk met aarde bedekt fort worden de aarden hellingen aangegeven als hoogteverschil, terwijl zichtbare muren aangegeven worden als muur, indien deze muur langer is dan 50 meter en hoger dan 2 meter. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **gemaal** |
| Definitie | Installatie om water omhoog te pompen uit een polder of een kanaal. |
| Inwinningscriteria | Alleen een gemaal, gelegen in het hoofdafwateringspatroon wordt aangegeven. Indien het object niet voldoet aan de criteria voor een gebouwvlak, dan wordt deze opgenomen als gebouwpunt.<br>Een gemaal moet altijd in combinatie met een waterdeel gegeven worden.<br>Een rioolgemaal wordt niet aangegeven als gemaal. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **gemeentehuis** |
| Definitie | Gebouw waarin de gemeentelijke secretarie gevestigd is. |
| Inwinningscriteria | Dependances van deze secretarie worden als 'stadskantoor, hulpsecretarie' aangegeven. Indien het gemeentehuis omwille van ruimtegebrek over verschillende gebouwen is verspreid, is er geen sprake van dependances. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **gevangenis** |
| Definitie | Gebouwen waarin personen in verzekerde bewaring worden gesteld. |
| Inwinningscriteria | Door middel van het attribuut soortnaam wordt vermeld of het eventueel een jeugdinrichting of detentiecentrum betreft. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **hotel** |
| Definitie | Gebouw ten behoeve van de overnachting van reizigers. |
| Inwinningscriteria | Een jeugdherberg wordt als hotel ingewonnen. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **huizenblok** |
| Definitie | Terrein, volledig of nagenoeg volledig bedekt met bebouwing (niet zijnde lintbebouwing of grote boerderijen met bijbehorende stallen), gelegen in stedelijk/verstedelijkt gebied, waarbij de bebouwing naar alle zijden aaneengesloten is en waar men vanaf de openbare weg van eventuele binnenplaatsen en -tuinen weinig of niets kan zien. |
| Inwinningscriteria | Bij de beoordeling of een zijde aaneengesloten is wordt alle bebouwing meegerekend, plus muren. Kleine openingen tot plm. 3 meter en poorten worden als bebouwd beschouwd. Grotere inspringingen welke niet voor het publiek vanaf de openbare weg toegankelijk zijn, worden bij het bebouwd gebied getrokken. Kleine en smalle inspringingen (tot plm. 3 meter) in de begrenzingslijn worden niet aangegeven. Ingeval het bebouwd gebied slechts uit één of enkele gebouwen bestaat, mogen binnenplaatsen gegeven worden indien deze groter zijn dan plm. 1000m². |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **kapel** |
| Definitie | Gebouwtje dat dient als bidruimte. |
| Inwinningscriteria | Indien het object niet voldoet aan de criteria voor een gebouwvlak, dan wordt deze opgenomen als gebouwpunt. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **kas, warenhuis** |
| Definitie | Voornamelijk uit glas opgebouwde overbouwing van de grond. |
| Inwinningscriteria | Een kas wordt aangegeven als een gebouw van het type kas, warenhuis, indien groter dan 200 m². Stookhokken worden als typegebouw 'overig' opgenomen. Plastic kassen met een permanent karakter worden ingewonnen als 'kas, warenhuis'. Het zogenaamde "platte glas" wordt niet aangegeven. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **kasteel** |
| Definitie | Burcht. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **kerk** |
| Definitie | Bebouwing bedoeld voor christelijke erediensten. |
| Inwinningscriteria | Een gebouw, dat is gebouwd met het doel om er christelijke erediensten te kunnen houden en door een kenmerkende bouwstijl als zodanig herkenbaar is, maar dat niet meer in gebruik is voor erediensten, wordt aangegeven als gebouw en voorzien van een typering die overeenkomt met het huidige gebruik alsmede van de soortnaam "Voormalige kerk". |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **kerncentrale, kernreactor** |
| Definitie | Centrale die met kernenergie elektriciteit opwekt (kerncentrale) / Installatie voor het splijten of fuseren van atoomkernen, atoomreactor (kernreactor). |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **kliniek, inrichting, sanatorium** |
| Definitie | Inrichting waar patiënten worden verpleegd (kliniek). / Herstellingsoord (sanatorium). |
| Inwinningscriteria | Ook een revalidatiecentrum wordt opgenomen. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **klokkentoren** |
| Definitie | Toren t.b.v. de ophanging van een klokkenspel (met tenminste 8 klokken). |
| Inwinningscriteria | Torens met minder dan 8 klokken of alleen een uurwerk worden gegeven als toren en niet als klokkentoren. Een klokkentoren welke niet voldoet aan de opnamecriteria voor een gebouwvlak, wordt aangegeven als gebouwpunt. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **klooster, abdij** |
| Definitie | Gebouw bedoeld voor de huisvesting en eventueel het voorzien in levensonderhoud van een geloofsgemeenschap. |
| Inwinningscriteria | Het hoofdgebouw wordt aangegeven als bebouwing en voorzien van de attribuutwaarde klooster/abdij. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **koeltoren** |
| Definitie | Torenvormig bouwsel voor het afkoelen van gassen of dampen. |
| Inwinningscriteria | Indien de koeltoren niet voldoet aan het voorschrift voor bebouwing wordt er een gebouwpunt geplaatst. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **koepel** |
| Definitie | Bolvormige constructie als dak van een gebouw. |
| Inwinningscriteria | Alleen een hoge koepel (in verhouding tot de omliggende bebouwing) wordt aangegeven.<br>Indien de koepel niet voldoet aan het voorschrift voor gebouwvlak wordt er een gebouwpunt geplaatst. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **kunstijsbaan** |
| Definitie | Gebouw voorzien van een installatie waarmee een ijsvloer kan worden gelegd. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **lichttoren** |
| Definitie | Toren als drager van een ter oriëntatie dienend licht, met name langs de kust. Het lichtpatroon van een lichttoren is niet uniek t.o.v. andere lichttorens. |
| Inwinningscriteria | Een **lichttoren** welke niet voldoet aan de opnamecriteria voor **gebouwvlak**, wordt aangegeven als een gebouwpunt. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **luchtwachttoren** |
| Definitie | Toren vroeger gebruikt t.b.v. het bewaken van het luchtruim. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **manege** |
| Definitie | Besloten plaats tot beoefening van het paardrijden. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **markant gebouw** |
| Definitie | Gebouw dat sterk opvalt ten opzichte van zijn omgeving. |
| Inwinningscriteria | Indien het object niet voldoet aan de criteria voor een gebouwvlak, dan wordt deze opgenomen als gebouwpunt. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **militair gebouw** |
| Definitie | Gebouw in gebruik voor militaire doeleinden. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **moskee** |
| Definitie | Bebouwing bedoeld voor islamitische geloofsuitoefening. |
| Inwinningscriteria | Een gebouw, dat is gebouwd met het doel om er islamitische geloofsuitoefening te kunnen houden en door een kenmerkende bouwstijl als zodanig herkenbaar is, maar dat niet meer in gebruik is voor geloofsuitoefening, wordt aangegeven als gebouw en voorzien van een typering die overeenkomt met het huidige gebruik alsmede van de soortnaam "Voormalige moskee". |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **museum** |
| Definitie | Gebouw waarin voorwerpen van kunst of wetenschap bijeen zijn gebracht en (ten minste voor een gedeelte) voortdurend uitgestald worden. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **observatorium** |
| Definitie | Gebouw t.b.v. het doen van waarnemingen in de ruimte. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **overig religieus gebouw** |
| Definitie | Bebouwing bedoeld voor geloofsuitoefening, niet zijnde een kerk, moskee en synagoge. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **paleis** |
| Definitie | Gebouw met een openbare of ceremoniële functie heeft voor gebruik door de koninklijke familie. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **parkeerdak, parkeerdek, parkeergarage** |
| Definitie | Al dan niet open bebouwing, geheel of gedeeltelijk (het dak of een van de onderliggende etages) in gebruik als openbare voorziening voor het parkeren van motorvoertuigen. |
| Inwinningscriteria | De toegang van een ondergrondse parkeergarage wordt aangegeven als een gebouwpunt. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **peilmeetstation** |
| Definitie | Installatie die informatie geeft over de landelijke/regionale waterstanden via het Monitoring Systeem Water (MSW). De installatie is voorzien van een Digitaal Niveau Meter (DNM). |
| Inwinningscriteria | Indien het object niet voldoet aan de criteria voor gebouwvlak, dan wordt deze opgenomen als gebouwpunt. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **politiebureau** |
| Definitie | Gebouw waarin een kantoor of bezoeklocatie van de politie is gevestigd. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **pompstation** |
| Definitie | Installatie waarmee een vloeistof op- of doorgepompt wordt. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **postkantoor** |
| Definitie | Kantoor waar men administratieve handelingen kan verrichten ten behoeve van postverzending, giro e.d.. |
| Inwinningscriteria | Alle locaties die PostNL als postkantoor aanduidt, worden als 'postkantoor' ingewonnen. Pakketpunten, businesspoints en andere locaties waar niet alle diensten van een postkantoor worden aangeboden, worden niet ingewonnen als 'postkantoor'. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **psychiatrisch ziekenhuis, psychiatrisch centrum** |
| Definitie | Verzorgingstehuis voor geesteszieken. |
| Inwinningscriteria | Het hoofdgebouw wordt voorzien van de attribuutwaarde psychiatrisch ziekenhuis, psychiatrisch centrum |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **radarpost** |
| Definitie | Plaats waar waarnemingen worden gedaan met behulp van radar, m.n. om vliegtuigen en scheepsbewegingen te observeren. |
| Inwinningscriteria | Een radarpost welke niet voldoet aan de opnamecriteria voor gebouwvlak, wordt aangegeven als gebouwpunt. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **radartoren** |
| Definitie | Toren t.b.v. radarsignalering c.q. radargeleiding. |
| Inwinningscriteria | Indien het object niet voldoet aan de criteria voor een gebouwvlak, dan wordt deze opgenomen als gebouwpunt. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **radiotoren, televisietoren** |
| Definitie | Toren t.b.v. het verspreiden van radio- en televisiesignalen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **recreatiecentrum** |
| Definitie | Terrein van min of meer beperkte omvang, bedoeld voor vrijetijdsbesteding. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **reddingboothuisje** |
| Definitie | Plaats waar een reddingboot beschikbaar is. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **remise** |
| Definitie | Wagenloods voor openbare vervoermiddelen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **ruïne** |
| Definitie | Overblijfsel van een verwoest of door ouderdom vervallen gebouw. |
| Inwinningscriteria | Minimaal een deel van een muur van een gebouw moet nog overeind staan om als ruïne gegeven te worden. Alleen een gebouw als ruïne aangeven als het een historisch gebouw is (in terrein te zien aan bebording, naamgeving, gedenkteken, etc.). Als een (niet historisch) gebouw / huis vervallen of verwoest is, dan wordt dit gebouw aangeven volgens voorkomen met de status buiten gebruik.<br>Indien het object niet voldoet aan de criteria voor een gebouwvlak, dan wordt deze opgenomen als gebouwpunt. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **schaapskooi** |
| Definitie | Stal voor schapen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **school** |
| Definitie | Gebouw in gebruik voor basis, middelbaar of hoger onderwijs. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **schoorsteen** |
| Definitie | Pijp voor het afvoeren van verbrandingsgassen. |
| Inwinningscriteria | Minimum hoogte 15 meter.<br>Indien het object niet voldoet aan de criteria voor een gebouwvlak, dan wordt deze opgenomen als gebouwpunt. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **silo** |
| Definitie | Gebouw in gebruik als opslagplaats voor stort- of bulkgoederen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **sporthal** |
| Definitie | Hal waarin kan worden gesport. |
| Inwinningscriteria | Grootschalige voorziening met een meer regionale uitstraling en meerdere velden t.b.v. verschillende of een specifieke tak van sport. |
						 
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **stadion** |
| Definitie | Gebouw met tribunes en een sportveld voor het beoefenen van sport, in het bijzonder voor het houden van grote wedstrijden. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **stadskantoor, hulpsecretarie** |
| Definitie | Bureau waar gemeentelijke instellingen, bijvoorbeeld de burgerlijke stand, gevestigd zijn. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **stationsgebouw** |
| Definitie | Een gebouw dat speciaal bedoeld is voor het bedienen van treinreizigers. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **synagoge** |
| Definitie | Bebouwing bedoeld voor joodse geloofsuitoefening. |
| Inwinningscriteria | Een gebouw, dat is gebouwd met het doel om er joodse erediensten te kunnen houden en door een kenmerkende bouwstijl als zodanig herkenbaar is, maar dat niet meer in gebruik is voor erediensten, wordt aangegeven als gebouw en voorzien van een typering die overeenkomt met het huidige gebruik alsmede van de soortnaam "Voormalige synagoge". |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **tank** |
| Definitie | Rond bouwwerk t.b.v. opslag. |
| Inwinningscriteria | Minimum diameter: 8 meter (bij een liggende tank geldt de breedtemaat), uitgezonderd een markante, alleenstaande tank. Zowel open als gesloten, zowel staand als liggend. Meerdere tanks met kleinere doorsnede worden niet aangegeven. Bijvoorbeeld gasbol, graansilo, mestsilo of olietank. Een niet-ronde graansilo wordt als 'overig' gebouw ingewonnen. Een niet-ronde waterbak groter dan 50 m² wordt opgenomen als waterdeel van het type 'meer, plas, ven, vijver'. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **tankstation** |
| Definitie | Inrichting waar motorbrandstof, olie, lucht en koelwater kunnen worden verkregen. |
| Inwinningscriteria | Wordt ingewonnen als gebouwvlak langs autosnelwegen en hoofdwegen.<br>Op de plek waar de pompen zijn gesitueerd, wordt altijd een gebouwpunt gegeven. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **telecommunicatietoren** |
| Definitie | Toren t.b.v. datacommunicatie. |
| Inwinningscriteria | Een telecommunicatietoren die niet voldoet aan de opnamecriteria voor gebouwvlak, wordt aangegeven als een gebouwpunt. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **tol** |
| Definitie | Een tol is een gebouw aan een verkeers- of waterweg waar tol wordt geheven. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **toren** |
| Definitie | Vrijstaand bouwwerk van grote hoogte in verhouding tot de doorsnede. |
| Inwinningscriteria | Een toren kan zowel vrijstaand als onderdeel van een groter stuk aaneengesloten bebouwing voorkomen.<br>Indien het object (vrijstaand of als onderdeel van een gebouw) niet voldoet aan de criteria voor gebouwvlak, dan wordt deze opgenomen als gebouwpunt.<br>Een starttoren wordt niet als toren opgenomen maar als overig gebouw. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **transformatorstation** |
| Definitie | Installatie voor het transformeren van elektrische stroom. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **uitzichttoren** |
| Definitie | Toren t.b.v. de recreatie. |
| Inwinningscriteria | Indien het object niet voldoet aan de criteria voor een gebouwvlak, dan wordt deze opgenomen als gebouwpunt. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **universiteit** |
| Definitie | Instelling voor wetenschappelijk onderwijs met tenminste drie faculteiten. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **veiling** |
| Definitie | Gebouw waar goederen openbaar worden geveild. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **verkeerstoren** |
| Definitie | Toren t.b.v. verkeersregulatie te land, ter zee of in de lucht. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **vuurtoren** |
| Definitie | Toren als drager van een ter oriëntatie dienend licht, met name langs de kust. Het lichtpatroon van de vuurtoren is uniek t.o.v. elke andere vuurtoren of lichttoren. |
| Inwinningscriteria | Alleen de torens, voorkomend op de "Vuurtorenlijst" worden als **vuurtoren** aangegeven.<br>Een voormalige vuurtoren, die nog steeds als zodanig herkenbaar is, wordt aangegeven als bebouwing en voorzien van de attribuutwaarde vuurtoren, waarbij de status op buiten gebruik wordt ingesteld. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **waterradmolen** |
| Definitie | Bebouwing t.b.v. het verrichten van arbeid, waarvoor de energie geleverd wordt door stromend water en opgenomen wordt door middel van een schoepenrad. |
| Inwinningscriteria | Een voormalige waterradmolen (zonder schoepenrad) wordt aangegeven als bebouwing zonder verdere toevoeging. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **watertoren** |
| Definitie | Toren (oorspronkelijk) bedoeld voor de opslag van drinkwater. |
| Inwinningscriteria | Niet de functie, maar het voorkomen telt. Een voormalige watertoren, die nog steeds als zodanig herkenbaar is, wordt opgenomen, met als status 'buiten gebruik'. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **wegrestaurant** |
| Definitie | Restaurant op verzorgingsplaats langs autosnelweg of hoofdweg. |
						 
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **werf** |
| Definitie | Werkplaats waar schepen worden gebouwd of hersteld. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **windmolen** |
| Definitie | Bebouwing t.b.v. het verrichten van arbeid (m.u.v. het opwekken van elektrische energie, het malen van granen en het opvijzelen van water), waarvoor de energie geleverd wordt door wind en opgenomen wordt door middel van wieken. |
| Inwinningscriteria | Indien het object niet voldoet aan de criteria voor gebouwvlak, dan wordt deze opgenomen als gebouwpunt.<br>Een voormalige windmolen zonder wieken wordt niet aangegeven als windmolen. Wanneer de wieken vanwege restauratie tijdelijk afwezig zijn, dan wordt het object wel als windmolen gegeven. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **windmolen: korenmolen** |
| Definitie | Bebouwing t.b.v. het malen van granen, waarvoor de energie geleverd wordt door wind en opgenomen wordt door middel van wieken. |
| Inwinningscriteria | Indien het object niet voldoet aan de criteria voor gebouwvlak, dan wordt deze opgenomen als gebouwpunt.<br>Een voormalige windmolen zonder wieken wordt niet aangegeven als windmolen: korenmolen. Wanneer de wieken vanwege restauratie tijdelijk afwezig zijn, dan wordt het object wel als windmolen: korenmolen gegeven. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **windmolen: watermolen** |
| Definitie | Bebouwing t.b.v. het opvijzelen van water, waarvoor de energie geleverd wordt door wind en opgenomen wordt door middel van wieken. |
| Inwinningscriteria | Indien het object niet voldoet aan de criteria voor gebouwvlak, dan wordt deze opgenomen als gebouwpunt.<br>Een voormalige windmolen zonder wieken wordt niet aangegeven als windmolen: watermolen. Wanneer de wieken vanwege restauratie tijdelijk afwezig zijn, dan wordt het object wel als windmolen: watermolen gegeven. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **windturbine** |
| Definitie | Bebouwing t.b.v. het opwekken van elektrische energie, waarvoor de energie geleverd wordt door wind en opgenomen wordt door middel van wieken. |
| Inwinningscriteria | Een windturbine wordt ingewonnen als gebouwpunt. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **zendtoren** |
| Definitie | Toren met een zendantenne. |
| Inwinningscriteria | Een zendtoren welke niet voldoet aan de opnamecriteria voor gebouwvlak, wordt aangegeven als een gebouwpunt. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **ziekenhuis** |
| Definitie | Instelling voor onderzoek, behandeling en verpleging van patiënten. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **zwembad** |
| Definitie | Gebouw met zwemfunctionaliteit of een zwembassin, openbaar toegankelijk. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GB\_typeGebouw |
|:---|:---|
| Domeinwaarde | **overig** |
| Definitie | De waarde van het objectkenmerk is bekend, maar anders dan de genoemde waarden. |
| Inwinningscriteria | De meeste gebouwen in TOP10NL zijn van het type "overig". Bijvoorbeeld woningen en flats, maar ook een stookhok bij een kas, kapschuur (schuur, bestaande uit een dak op palen en maximaal één muur), KI-station (gebouw waarin of van waar uit handelingen tot kunstmatige inseminatie uitgevoerd worden) of starttoren. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |


## 7.11 Objectklasse: geografisch gebied

_Definitie:_

Begrensd en benoemd gebied dat door een geografische eenheid beschreven wordt.

_Inwinningscriteria:_

\-

### Attribuut labelPunt

| Attribuut | labelPunt |
|:---|:---|
| Definitie | De puntgeometrie van een geografisch gebied object. |
												 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Point |
| Domein | "Ruimtelijke coördinaten" |
							

### Attribuut geometrieVlak

| Attribuut | geometrieVlak |
|:---|:---|
| Definitie | De vlakgeometrie van een geografisch gebied object. |
																												 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Surface of GM\_MultiSurface |
| Domein | "Ruimtelijke coördinaten" |
							

### Attribuut type geografisch gebied

| Attribuut | type geografisch gebied |
|:---|:---|
| Definitie | Het soort geografisch gebied. |
												 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "GG\_typeGeografischGebied" |
							

#### Domein "GG\_typeGeografischGebied"

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **bank, ondiepte, plaat** |
| Definitie | Geheel of gedeeltelijk droogvallende grond (bank). / Ondiepe plaats in een vaarwater (ondiepte). / Zandbank (plaat). |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **bosgebied** |
| Definitie | Met bos begroeid gebied. |
																																																															
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **duingebied** |
| Definitie | Heuvels van fijn zand, al dan niet begroeid met helmgras en struiken. |
																																																																																																																									
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **eiland** |
| Definitie | Land, omgeven door water. |
																																					 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **geul, vaargeul** |
| Definitie | Smal, meestal diep water (geul). / Geul van voldoende diepte als vaarwater tussen ondiepten door (vaargeul). |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **heidegebied** |
| Definitie | Met heide begroeid gebied. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **heuvel, berg** |
| Definitie | Verhoging van het terrein (heuvel). / Min of meer op zichzelf staande sterke verheffing van het aardoppervlak (berg). |
| Inwinningscriteria | Alleen duintoppen met een eigennaam krijgen een geografisch gebied. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **kaap, hoek** |
| Definitie | In zee vooruitstekende landpunt (kaap). / In het water uitstekende landtong (hoek). |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **polder** |
| Definitie | Door waterscheidingen begrensd stuk land of gebied waarin de waterstand kan worden beheerst door bemaling. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **streek, veld** |
| Definitie | Landstreek, gebied dat cultureel of landschappelijk een eenheid vormt (streek). / Het open land buiten steden en dorpen (veld). |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **terp, wierde** |
| Definitie | Verhoging in het landschap oorspronkelijk bedoelt om de daarop gevestigde bebouwing te beschermen tegen het water. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **wad** |
| Definitie | De buitendijkse gronden bij Friesland, Groningen en Noord-Duitsland die alleen bij vloed onder water komen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **watergebied** |
| Definitie | Een complex van meren en plassen. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **zee** |
| Definitie | Uitgestrekt oppervlak zout water dat het grootste deel van de aarde bedekt. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **zeegat, zeearm** |
| Definitie | Plaats waar een binnenzee in een zee uitmondt (zeegat). /<br>Lange, smalle inham van een zee (zeearm). |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

							
| Domein | GG\_typeGeografischGebied |
|:---|:---|
| Domeinwaarde | **overig** |
| Definitie | De waarde van het objectkenmerk is bekend, maar anders dan de genoemde waarden. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
### Attribuut naam (Nl)

| Attribuut | naam (Nl) |
|:---|:---|
| Definitie | De Nederlandse naam van het geografisch gebied. |
| Inwinningscriteria | Een woonwijk mag de tekst 'Stadswijk in aanleg' of 'Woonwijk in aanleg' als naam hebben. |
| Volledigheid | Beperkt |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut naam (Fr)

| Attribuut | naam (Fr) |
|:---|:---|
| Definitie | De Friese naam van het geografisch gebied. |
| Inwinningscriteria | Wordt alleen in Friesland ingewonnen. |
| Volledigheid | Beperkt |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |


## 7.9 Objectklasse: hoogte

_Definitie:_

Virtuele objecten met informatie over de hoogte van het terrein of de diepte van het water.

_Inwinningscriteria:_

\-

### Attribuut geometriePunt

| Attribuut | geometriePunt |
|:---|:---|
| Definitie | De puntgeometrie van een hoogte object. |
																		 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Point |
| Domein | "Ruimtelijke coördinaten" |
							

### Attribuut geometrieLijn

| Attribuut | geometrieLijn |
|:---|:---|
							 
| Definitie | De lijngeometrie van een hoogte object. |
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Curve |
| Domein | "Ruimtelijke coördinaten" |
							

### Attribuut referentievlak

| Attribuut | referentievlak |
|:---|:---|
| Definitie | Het referentievlak waarop de hoogte van het object gebaseerd is. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "HO\_referentievlak" |
							

#### Domein "HO\_referentievlak"

| Domein | HO\_referentievlak |
|:---|:---|
| Domeinwaarde | **NAP** |
| Definitie | Normaal Amsterdams Peil. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
							

| Domein | HO\_referentievlak |
|:---|:---|
| Domeinwaarde | **LAT** |
| Definitie | Lowest Astronomical Tide. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
							

| Domein | HO\_referentievlak |
|:---|:---|
| Domeinwaarde | **GHW** |
| Definitie | Gemiddeld Hoog Water. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

| Domein | HO\_referentievlak |
|:---|:---|
| Domeinwaarde | **OLW** |
| Definitie | Overeengekomen Laag Water. |
						 
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
							

### Attribuut type hoogte
				 
						 
						

| Attribuut | type hoogte |
|:---|:---|
						
| Definitie | Het soort hoogte. |
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "HO\_typeHoogte" |
							

#### Domein "HO\_typeHoogte"

| Domein | HO\_typeHoogte |
|:---|:---|
| Domeinwaarde | **dieptelijn** |
| Definitie | Lijn gevormd door punten met gelijke waterdiepte. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |
							

| Domein | HO\_typeHoogte |
|:---|:---|
| Domeinwaarde | **dieptepunt** |
| Definitie | Punt waarvan de waterdiepte bekend is ten opzichte van het referentievlak. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |
							

| Domein | HO\_typeHoogte |
|:---|:---|
| Domeinwaarde | **hoogtelijn** |
| Definitie | Lijn die punten van gelijke hoogte met elkaar verbindt. |
| Inwinningscriteria | De hoogtelijnen zijn automatisch gegenereerd uit het hoogtemodel zonder rekening te houden met in het landschap aanwezige kunstmatige elementen, zoals wallen en dijken. Deze kunstmatige elementen met hoogte zijn ingewonnen als Reliëf-object. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | HO\_typeHoogte |
|:---|:---|
| Domeinwaarde | **hoogtepunt** |
| Definitie | Punt in de kaart, waarvan de hoogte bekend is ten opzichte van het referentievlak. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |
							

| Domein | HO\_typeHoogte |
|:---|:---|
| Domeinwaarde | **hoogwaterlijn** |
| Definitie | Lijn die de grens van het water aangeeft als de waterstand op zijn hoogst is. |
| Inwinningscriteria | De hoogwaterlijn is onderdeel van TOP10NL vanwege INSPIRE eisen en wordt ingewonnen in de 6 grote wateren in Nederland (Noordzee, Waddenzee, IJsselmeer, Markermeer, Oosterschelde en Westerschelde). |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | HO\_typeHoogte |
|:---|:---|
| Domeinwaarde | **laagwaterlijn** |
| Definitie | Lijn die de grens van het water aangeeft als de waterstand op zijn laagst is. |
| Inwinningscriteria | Door middel van het attribuut referentievlak wordt aangegeven op welke waterstand deze lijn gebaseerd is. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | HO\_typeHoogte |
|:---|:---|
| Domeinwaarde | **peil** |
| Definitie | Geeft de streefhoogte aan van het waterniveau t.o.v. het referentievlak in grotere waterplassen. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |
							

| Domein | HO\_typeHoogte |
|:---|:---|
| Domeinwaarde | **peil: winterpeil** |
| Definitie | Geeft de streefhoogte aan van het waterniveau t.o.v. het referentievlak in grotere waterplassen gedurende de wintermaanden. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |
							

| Domein | HO\_typeHoogte |
|:---|:---|
| Domeinwaarde | **peil: zomerpeil** |
| Definitie | Geeft de streefhoogte aan van het waterniveau t.o.v. het referentievlak in grotere waterplassen gedurende de zomermaanden. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |
							

### Attribuut hoogte

| Attribuut | hoogte |
|:---|:---|
| Definitie | Hoogte van het object t.o.v. het referentievlak in meters met een nauwkeurigheid van 1 decimeter. / De diepte van het water. |
| Inwinningscriteria | Wordt aangegeven voor hoogte- en dieptelijnen, hoogte- en dieptepunten en laagwaterlijnen. |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Decimaal getal |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

## 7.7 Objectklasse: inrichtingselement

_Definitie:_

Ruimtelijk object, punt- of lijnvormig, al dan niet ter detaillering dan wel ter inrichting van de overige benoemde ruimtelijke objecten of een ander inrichtingselement.

_Inwinningscriteria:_

Inrichtingspunten met een negatief hoogteniveau worden niet ingewonnen.

### Attribuut geometriePunt

| Attribuut | geometriePunt |
|:---|:---|
| Definitie | De puntgeometrie van een inrichtingselement object. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Point |
| Domein | "Ruimtelijke coördinaten" |

### Attribuut geometrieLijn

| Attribuut | geometrieLijn |
|:---|:---|
| Definitie | De lijngeometrie van een inrichtingselement object. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Curve |
| Domein | "Ruimtelijke coördinaten" |

### Attribuut type inrichtingselement

| Attribuut | type inrichtingselement |
|:---|:---|
| Definitie | Het soort inrichtingselement. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "IE\_typeInrichtingselement" |

#### Domein "IE\_typeInrichtingselement"

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **aanlegsteiger** |
| Definitie | In het water uitstekende brug of pier, smaller dan 2 meter, gebruikt om personen en goederen aan wal te brengen. |
| Inwinningscriteria | Minimum lengte 50 meter. De minimumlengte geldt niet indien de aanlegsteiger is gelegen in een waterdeel met de functie haven.<br>Wordt gegeneraliseerd weergegeven.<br><br>Een rij onderling verbonden meerpalen wordt ook ingewonnen als aanlegsteiger. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **baak** |
| Definitie | Markering van de loop van de vaargeul. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **bomenrij** |
| Definitie | Aantal bomen (minimaal 3) die in een rij staan, waarbij de onderlinge afstand tussen de bomen zodanig is dat de bomenrij tot manshoogte geen zichtbelemmering vormt. |
| Inwinningscriteria | Minimum lengte: 100 meter. Indien een doorgaande bomenrij in het terrein voor minder dan 100 meter onderbroken is, wordt de onderbreking genegeerd en de bomenrij doorgetrokken. Een grotere opening leidt tot een opsplitsing in twee bomenrijen. Dit geldt niet indien een bomenrij een weg, water e.d. kruist die als vlak wordt weergegeven. In dat geval mogen ze korter zijn dan 100 m mits ze onderdeel zijn van een logisch doorgaand geheel.<br>Een enkele boom in de lijn van een aanwezige bomenrij, maar op meer dan 50 meter afstand, hoeft niet als onderdeel van die bomenrij gerekend te worden.<br>Bij een bomenrij naast een weg wordt de lijn op het wegvlak geplaatst als de bomen staan in een bij de weg getrokken berm, en buiten het wegvlak als de bomen staan op een niet bij de weg getrokken berm. Wordt binnen bebouwd gebied slechts gegeven indien gelegen langs een naar breedte geclassificeerde weg. Parallel gelegen fietspaden langs geclassificeerde wegen worden eveneens voorzien van bomenrijen.<br>Wordt in een bos alleen aangegeven als er sprake is van een markante laan (b.v. oprijlaan naar een kasteel).<br>Een bomenrij op of om een erf mag worden gegeven indien deze door loopt in het achter- of naastliggende terrein.<br>Een bomenrij gelegen op de weg langs een waterdeel wordt, indien het betreffende waterdeel voor minder dan 100m wordt onderbroken, zonder verspringing doorgetrokken. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **boom** |
| Definitie | Houtachtig gewas met een enkele, stevige, houtige en overblijvende stam, die zich op een zekere hoogte boven de grond vertakt. |
| Inwinningscriteria | Bomen worden gegeneraliseerd ingewonnen.<br>Bomen binnen bebouwd gebied op of langs een straat, in een tuin of op een erf worden niet opgenomen tenzij gelegen in plantsoen of park.<br>Een permanent aanwezige boom op een kwekerij kan gegeven worden.<br>Een klein aantal bij elkaar staande bomen wordt als één boom opgenomen.<br>Een gewas met meerdere hoofdstammen vanuit hetzelfde wortelstelsel (geen struik) wordt gegeven als boom. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **botenhelling** |
| Definitie | Voorziening om boten uit of in het water te helpen. |
| Inwinningscriteria | Geeft het begin van de helling aan.<br>Wordt met behulp van het attribuut soortnaam geclassificeerd als openbare botenhelling of niet-openbare botenhelling. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **busstation** |
| Definitie | Een plaats waar verschillende buslijnen samenkomen en waar meerdere bushaltes aanwezig zijn, met het doel dat buspassagiers hier kunnen in-, uit- of overstappen. |
| Inwinningscriteria | |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **calamiteitendoorgang** |
| Definitie | Doorgang in de verkeersgeleider of wegafsluiting die hulpdiensten doorgang moet verlenen voor het bestrijden van calamiteiten. |
| Inwinningscriteria | |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **dukdalf** |
| Definitie | In het water geplaatste, zware al dan niet metalen paal of constructie, dienend tot bescherming van bruggen en sluizen. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **gaswinning** |
| Definitie | Installatie t.b.v. de winning of transport van aardgas. |
| Inwinningscriteria | Maximum oppervlakte: 1000 m². Indien groter, dan wordt het opgenomen als functioneel gebied. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **gedenkteken, monument** |
| Definitie | Topografisch object ter nagedachtenis van een belangrijke persoon of gebeurtenis. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **geluidswering** |
| Definitie | Constructie ten behoeve van het terugdringen van geluidsoverlast. |
| Inwinningscriteria | Minimum lengte: 100 meter. Minimum hoogte: 2 meter.<br>Een geluidsscherm op een dijk wordt ingewonnen als 'geluidswering'.<br>Een wal met geluidsscherm, samen hoger dan 2 meter, wordt ingewonnen als 'geluidswering'. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **golfmeetpaal** |
| Definitie | Paal uitgerust met instrumenten t.b.v. het doen van waarnemingen betreffende golfbewegingen. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Attribuutwaarde | **GPS kernnetpunt** |
| Definitie | Punt geschikt voor GPS metingen (kan een steen of bout zijn). |
| Inwinningscriteria | Alleen recent gecontroleerde GPS-kernnetpunten worden opgenomen in de BRT. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **grenspunt** |
| Definitie | Aanduiding van een grensscheiding. |
| Inwinningscriteria | Bij een herziening worden grenspalen alleen gecontroleerd in de buurt van nieuwe topografie. Overige grenspalen worden niet gecontroleerd. Op een gemeentegrens of provinciegrens worden alleen grote, markante palen aangegeven (een stalen paal met een gemeentenaambordje wordt niet als markant gezien). Indien er langs de grens dubbele grenspalen aanwezig zijn (bijvoorbeeld aan weerszijden van een waterloop) wordt er slechts één gegeven. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **havenhoofd** |
| Definitie | Zware, stenen of houten dam ter weerszijden van de mond van een haven. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **heg, haag** |
| Definitie | Rij bomen, al of niet in combinatie met struiken, waarbij de onderlinge afstand of onderbegroeiing zodanig is dat tot minstens manshoogte het zicht belemmerd wordt. Maximale inplantbreedte van de stammen: 3 meter. / Een rij naast elkaar geplante struiken (liguster, haagdoorn, coniferen, haagbeuk, e.d.) die op gezette tijden worden geschoren. Minimale hoogte 1 meter, minimumlengte: 100 meter. |
| Inwinningscriteria | - Wordt niet opgenomen binnen bebouwd gebied en tussen tennisbanen. Een heg, haag op of rondom een erf wordt niet ingewonnen, tenzij deze zich voortzet voorbij het erf.<br>- Een heg/haag aan de buitenzijde van een bos of op een middenberm smaller dan 6 meter of op het bovenste gedeelte van een talud wordt niet opgenomen. Een heg/haag in een berm smaller dan 6 meter wordt aan de buitenzijde van het wegdeel geplaatst (de berm is onderdeel van het wegdeel), maar als het wegdeel wordt begrensd door een watervlak of een talud, hoogteverschil, dan wordt de heg/haag voorgesteld als bomenrij aan de binnenzijde van het wegdeel, een haag wordt niet aangegeven. Als het aan de weg grenzende vlak een weer te geven talud betreft dan wordt een heg gegeven als bomenrij op het talud, een haag wordt in dat geval niet gegeven.<br>- Een heg / haag gelegen op het onderste gedeelte van een talud wordt aangegeven aan de voet van het talud indien hiervoor ruimte is, waarbij de voorstelling van de heg blijft liggen binnen het vlak waarin ook het talud ligt. Is er niet voldoende ruimte aan de voet van het talud voor het geven van de heg/ haag dan wordt deze aan de buitenzijde van het taludvlak geplaatst. Indien echter het begrenzende vlak een waterloop > 6m betreft geldt dat een heg gegeven wordt als bomenrij op de werkelijke plaats, een haag wordt in dat geval niet gegeven.<br>- Een rij dicht op elkaar geplante bomen met de functie van windscherm wordt gegeven als heg.<br>- Doorgangen dienen gegeven te worden in geval van gelegen langs een door een koedam of duiker onderbroken waterdeel of indien vrijliggend gelegen in open, landelijk gebied. Geen doorgangen geven indien gelegen langs erven, wegen en op campings. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **hekwerk** |
| Definitie | Begrenzing van een terrein in de vorm van een afrastering. |
| Inwinningscriteria | Minimumlengte: 400 meter bij gas- en oliewinningsgebieden, 1000 meter in overige situaties.<br>Minimumhoogte: 2 meter. Bij een combinatie van hekwerken op een bedrijventerrein of op het terrein van een groot bedrijf wordt het buitenste hekwerk opgenomen. Daarbinnen worden hekwerken selectief ingewonnen. Wordt niet ingewonnen tussen tennisbanen.<br>Indien een afrastering dwars over een weg loopt en ter plaatse een draaihek, slagboom o.i.d. aanwezig is, wordt alleen bij de hoofd in- en uitgang van het omsloten terrein een wegafsluiting geplaatst. Indien de wegafsluiting niet gegeven wordt, wordt het hek doorgetrokken. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **helikopterlandingsplatform** |
| Definitie | Platform dat als landings- en vertrekplaats dient voor helikopters. |
| Inwinningscriteria | |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **hoogspanningsleiding** |
| Definitie | Leiding waarop elektrische spanning van meer dan 500 volt staat. |
| Inwinningscriteria | Zogenaamde wintrackmasten (magneetveldarme masten herkenbaar aan twee tegenover elkaar staande palen) worden gekarteerd door het geven van één hoogspanningsmast in het centrum. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **hoogspanningsmast** |
| Definitie | Mast van een hoogspanningsleiding. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **hunebed** |
| Definitie | Voorhistorische begraafplaats, bestaande uit opgestapelde, reusachtige stenen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **kaap** |
| Definitie | Gestel van balken met een daartegen aangebracht scherm van latten of ribben, dat als baak op het land dienst doet voor de zeevaart. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **kabelbaan** |
| Definitie | Kabel waaraan stoeltjes hangen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **kabelbaanmast** |
| Definitie | Mast van een kabelbaan. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **kilometerpaal** |
| Definitie | Paal waarop de kilometrering van een weg wordt aangegeven. |
| Inwinningscriteria | Alleen de palen met een gehele kilometeraanduiding worden aangegeven. Bij een weg met gescheiden rijbanen met een middenberm smaller dan 6 meter en met kilometeraanduiding aan beide zijden en eventueel in de middenberm, wordt toch slechts één aanduiding aangegeven; bij voorkeur rechts in oplopende richting. Bij een weg met gescheiden rijbanen met een middenberm breder dan 6 meter en met kilometeraanduiding aan beide zijden en eventueel in de middenberm, worden de aanduidingen links en rechts aangegeven, niet in de middenberm. Bij een weg met gescheiden rijbanen met alleen een kilometeraanduiding in de middenberm, wordt de aanduiding alleen in de middenberm aangegeven. Er wordt geen kilometrering gegeven langs op- en afritten met uitzondering van wegen die behoren tot een knooppunt. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **kilometerpaal spoorweg** |
| Definitie | Paal waarop de kilometrering van een spoorweg wordt aangegeven. |
| Inwinningscriteria | Alleen de palen met een gehele kilometeraanduiding worden aangegeven. Wordt niet ingewonnen langs metrolijnen. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **kilometerpaal water** |
| Definitie | Paal waarop de kilometrering van een water wordt aangegeven. |
| Inwinningscriteria | Alleen de palen met een gehele kilometeraanduiding worden aangegeven. Indien er alleen hectometerpalen aanwezig zijn, worden alleen de tientallen opgenomen. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **kilometerraaibord** |
| Definitie | Bord op de oever van een rivier, met daarop vermeld het aantal gehele kilometers van de betreffende kilometerraai. Een kilometerraai is een lijn loodrecht op de lengteas van een rivier, gedacht op onderlinge afstand van 1 kilometer als indeling van het traject. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **kilometerraaipaal** |
| Definitie | Paal, meestal geplaatst tegenover een kilometerraaibord, op de andere oever van de rivier. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **klokkenstoel** |
| Definitie | Stellage van balken (ongeacht het soort materiaal), meestal voorzien van een afdak, waarin een of meerdere klokken hangen. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **koedam** |
| Definitie | Onderbreking van een waterloop, door middel van demping, al dan niet met een doorlaatbuis. |
| Inwinningscriteria | Een duiker in open terrein, niet gelegen in het hoofdafwateringspatroon, wordt aangegeven als koedam.<br>Koedammen gelegen in waterlopen smaller dan 6 meter die onderdeel uitmaken van het hoofdafwateringspatroon worden opgenomen als duiker.<br>Een bredere koedam (breder dan 12 meter) wordt aangegeven met een onderbreking van het waterdeel.<br>Een onderbreking van een waterloop wordt altijd aangegeven tenzij gelegen in een wegcontour. Of er ook een inrichtingselement van het type koedam gegeven wordt is afhankelijk van een aantal randvoorwaarden. Er wordt geen inrichtingselement van het type koedam gegeven indien:<br>- de koedam is gelegen in of langs een bosperceel<br>- over de koedam een wegvlak, weglijn of dijk (reliëflijn) ligt.<br>- er geen sprake is van de mogelijkheid tot passage van de onderbreking (bv. i.h.g.v. aanwezigheid van een mast, windturbine, lantaarnpaal ed. op de dam).<br>- de te overbruggen afstand meer dan 12 m bedraagt.<br>- de waterdelen aan beide zijden van de dam breder zijn dan 6 meter. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **kogelvanger schietbaan** |
| Definitie | Zandheuvel of ander voorwerp achter de schietschijf op een schietbaan, die de afgevuurde kogels opvangt. |
| Inwinningscriteria | Wordt ingewonnen in combinatie met 'schietbaan'. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **kraan** |
| Definitie | Hijswerktuig om zware voorwerpen op te tillen en te verplaatsen. |
| Inwinningscriteria | Wordt niet ingewonnen. |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **kruis** |
| Definitie | Object tot bezinning en/of verering in de vorm van een kruis of heiligenbeeld. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **leiding** |
| Definitie | Koker, buis, draad enz. waardoor of waarlangs een stof of kracht geleid wordt. |
| Inwinningscriteria | Wordt niet ingewonnen |
| Volledigheid | Niet |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **luchtvaartlicht** |
| Definitie | Navigatielicht t.b.v. de luchtvaart. |
| Inwinningscriteria | Wordt niet ingewonnen |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **markant object** |
| Definitie | Een object dat vanuit de wijde omgeving zichtbaar is en een oriënterende waarde heeft. |
| Inwinningscriteria | Een object wordt als inrichtingselement van het type 'markant object' ingewonnen indien het niet kan worden opgenomen in een meer specifieke categorie (bebouwing, palen, gedenktekens, zendmasten, schoorstenen) waarbij voor kunstwerken en reclame-uitingen extra voorwaarden gelden:<br>Reclamemasten worden pas als markant object gegeven indien de mast reclame van meerdere bedrijven voert.<br>Kunstwerken worden pas opgenomen als markant object indien het object opvallend groot is (richtlijn: meer dan 5m hoog). Binnen bebouwd gebied worden ze genegeerd met uitzondering van kunstwerken die als blikvanger dienen langs de toegangswegen naar een stad of dorp en voldoen aan de gegeven richtlijn voor de maatvoering. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **metrostation** |
| Definitie | Halteplaats voor een onder- of bovengronds metronetwerk. |
| Inwinningscriteria | Geeft de ingang van het station aan. De ligging van een ondergronds metrostation wordt ontleend aan de plattegrond van de metro. Een eventueel stationsgebouw wordt niet als metrostation aangegeven maar als gebouw van het type 'stationsgebouw'. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **muur** |
| Definitie | Relatief smal, rechtopstaand bouwwerk. |
| Inwinningscriteria | Minimum lengte: 50 meter. Minimum hoogte: 2 meter. Voor een muraltmuur (muur geplaatst op een dijk met een waterkerende functie) geldt deze minimum hoogte niet. Een muur voor het bijzetten van urnen (columbarium) op een begraafplaats wordt niet opgenomen. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **oliepompinstallatie** |
| Definitie | Productie-installatie om olie uit de grond te pompen. |
| Inwinningscriteria | Per plateau wordt slechts één oliepompinstallatie geplaatst. Opnamecriterium is de aanwezigheid van de installatie, niet of deze wel of niet operationeel is. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **paal** |
| Definitie | Stevig, langwerpig, rechtop in de grond geplaatst merkteken ter afbakening. / Kilometrering van een dijklichaam. |
| Inwinningscriteria | Voor de kilometrering van een dijklichaam geldt: Alleen de palen met een gehele kilometeraanduiding worden aangegeven. Indien er alleen hectometerpalen aanwezig zijn, worden alleen de tientallen opgenomen. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **paalwerk** |
| Definitie | Palissade, omheining van in de grond geslagen palen of staken ten behoeve van landaanwinning. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **peilschaal** |
| Definitie | Lat met schaalverdeling voor het aflezen van de waterhoogte in een water. |
| Inwinningscriteria | Alleen aangegeven indien het in het hoofdafwateringspatroon ligt of buitendijks de grote rivieren. Wordt niet aangegeven in combinatie met een brug, duiker, gemaal, sluis of stuw. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **pijler** |
| Definitie | Zuil die een bouwconstructie ondersteunt. |
| Inwinningscriteria | Alleen pijlers van een brug die duidelijk buiten het brugdek uitsteken worden opgenomen. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **plaatsnaambord** |
| Definitie | Bord dat de naam weergeeft van een bewoond oord. |
| Inwinningscriteria | - |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **radiobaken** |
| Definitie | Radiozendstation op een vliegveld of langs een luchtroute, dat dient als hulpmiddel om de koers voor vliegtuigen te bepalen. |
| Inwinningscriteria | Wordt niet ingewonnen. |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **radiotelescoop** |
| Definitie | Instrument waarmee men radiogolven uit de kosmische ruimte kan opvangen. |
| Inwinningscriteria | Komt ook voor in een moderne variant waarbij in het landschap op regelmatige afstand sensoren staan opgesteld, er is geen sprake van een bouwwerk. In dat geval het terrein geven naar voorkomen en een inrichtingspunt plaatsen van het type overig met de naam Lofar. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **RD punt** |
| Definitie | Getrianguleerd punt. |
| Inwinningscriteria | Alleen recent gecontroleerde RD-punten worden opgenomen in de BRT. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **scheepvaartlicht** |
| Definitie | Stellage die een licht draagt t.b.v. de scheepvaart. |
| Inwinningscriteria | Ook de lichten langs het Noordzeekanaal worden ingewonnen. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **schietbaan** |
| Definitie | Baan ingericht voor het schieten naar een doel. |
| Inwinningscriteria | Wordt ingewonnen in combinatie met 'kogelvanger schietbaan'. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **seinmast** |
| Definitie | Mast waarin seinen worden gehesen. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **sluisdeur** |
| Definitie | Beweegbare waterkering van een (schut)sluis. |
| Inwinningscriteria | Per schutsluis komen twee of meer deuren voor, gescheiden door een tussenruimte. Alleen de voorste en achterste sluisdeur wordt ingewonnen.<br>Een sluis in of vlak bij een duiker wordt ingewonnen als waterdeel met fysiek voorkomen 'in afsluitbare duiker'.<br>Een sluisdeur gelegen onder een gebouw, een wegvlak of terreinvlak 'op brug', wordt geplaatst tussen het bovenliggende object en het watervlak. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **sneltramhalte** |
| Definitie | Halte aan een sneltramlijn. |
| Inwinningscriteria | Geeft de ingang van de halte aan. Een eventueel stationsgebouw wordt niet als sneltramhalte aangegeven maar als gebouw van het type 'stationsgebouw'. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **stormvloedkering** |
| Definitie | Waterkering, bedoeld om bij extreem hoge waterstanden water af te sluiten ter bescherming van het achter de kering gelegen land. |
| Inwinningscriteria | Alleen de schuiven worden opgenomen als inrichtingselement van het type stormvloedkering. De torens worden opgenomen als gebouw. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **strandpaal** |
| Definitie | Paal op het strand of in de duinen, geplaatst als hulpmiddel bij het uitvoeren van metingen. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **strekdam, krib, golfbreker** |
| Definitie | Dam in de richting van de loop van de rivier of kanaal, ter beveiliging van de oevers of brugpijlers of tot beperking van de rivier tot een bepaalde breedte (strekdam).<br>Golfslagbreker of stroombreker langs de kust en in rivieren, staat loodrecht op de oever/kust (krib).<br>Een uit steenglooiing of stortsteen bestaand object bedoelt voor oeverbescherming (golfbreker). |
| Inwinningscriteria | Wordt, indien breder dan 2 m, gegeven als steenglooiing.<br>Minimumlengte voor opname is 50 meter. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **stuw** |
| Definitie | Vaste of beweegbare constructie die dient om de waterstand bovenstrooms van de constructie te regelen. |
| Inwinningscriteria | Een stuw, in een duiker, wordt gekoppeld aan die duiker in de vorm van de attribuutwaarde 'in afsluitbare duiker' aan het bijbehorende waterdeel. Een grote stuw wordt aangegeven in gesloten toestand (b.v. de stuw bij Hagestein).<br>Een stuw tussen waterlijnen wordt aangegeven met een puntobject, een stuw tussen watervlakken wordt aangegeven met een lijnobject. Indien de stuw is gelegen tussen een waterlijn en watervlak wordt deze gegeven als puntobject. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **tol** |
| Definitie | Plaats waar men tol moet betalen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **treinstation** |
| Definitie | Halte aan een spoorlijn. |
| Inwinningscriteria | Geeft de ingang van het station aan. Een eventueel stationsgebouw wordt niet als treinstation aangegeven maar als gebouw van het type 'stationsgebouw'. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **uitzichtpunt** |
| Definitie | Punt met fraai uitzicht. / Bouwwerk permanent ingericht om te kunnen observeren. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **verkeersgeleider** |
| Definitie | Obstakel op een weg om het verkeer in goede banen te leiden. |
| Inwinningscriteria | Een verkeersgeleider wordt alleen gegeven indien deze is gelegen in een geclassificeerde weg (auto(snel)wegen, hoofdwegen, regionale en lokale wegen).<br>Minimum lengte 50 meter. Maximale breedte 6 meter.<br>Een verkeersgeleider kan zich over meerdere logisch verbonden wegen uitstrekken. Een logisch geheel kan pas gevormd worden indien er minimaal twee op zichzelf staande kruisingen bij betrokken zijn. De lengte van een verkeersgeleider wordt dan ook gemeten over de volle lengte van dit logisch geheel. De lengte van elk logisch verbonden gedeelte moet minimaal 6 meter zijn.<br>Een middenberm (smalle strook grond, aan beide zijden begrensd door rijbanen van dezelfde weg) wordt als verkeersgeleider opgenomen indien smaller dan 6 meter.<br>Een verkeersgeleider breder dan 6 meter wordt aangegeven als terrein, als deze tenminste 50 meter lang is.<br>Als de verkeersgeleider langer is dan 500 meter, worden beide wegen geclassificeerd als weg met gescheiden rijbanen, onafhankelijk van de breedte van de middenberm, mits beide wegen als een samenhangend geheel kunnen worden beschouwd. Er mag in dit geval geen verkeersgeleider tussen de rijbanen gegeven worden. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **vlampijp** |
| Definitie | Affakkelinstallatie. |
| Inwinningscriteria | Alleen markante vlampijpen worden ingewonnen. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **vliedberg** |
| Definitie | Verhoging in het terrein ter bescherming van de daarop geplaatste bebouwing tegen hoogwater. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **wegafsluiting** |
| Definitie | Een fysieke permanente of tijdelijke barrière in of dwars over een weg voor tenminste een gedeelte van de gebruikers van die weg. (b.v paaltjes, slagboom, toegangshek, etc.). |
| Inwinningscriteria | Een wegafsluiting in een bos wordt alleen opgenomen indien deze voorkomt op een verharde of halfverharde weg.<br>Paaltjes en zigzaghekken aan het begin, eind of in voet- en rijwielpaden worden niet opgenomen. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **wegwijzer** |
| Definitie | Richtingaanduiding. |
| Inwinningscriteria | Wordt alleen ingewonnen buiten bebouwd gebied, maar niet op autosnelwegen. Er wordt maximaal één wegwijzer per kruising ingewonnen. Een wegwijzer ten behoeve van de scheepvaart wordt niet ingewonnen.<br>De wegwijzer wordt geplaatst waar hij in het terrein voorkomt en mag dus ook midden op de weg voorkomen in het geval van een niet te geven (midden)berm of vluchtheuvel. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **windmolentje** |
| Definitie | Een vrij op de wind draaiend molentje (met wieken of een rad van schoepen) van metaal en/of kuststof, bestemd voor het bemalen van een sloot. / Klein type molen, herkenbaar aan schuin op een stellage geplaatste wieken, bestemd voor het bemalen van het omliggende terrein (tjasker). |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **zendmast** |
| Definitie | Telecommunicatietoren (toren t.b.v. datacommunicatie). / Zendtoren (toren met een zendantenne) / Zend- en/of ontvangstmast (hoge, open constructie t.b.v. het uitzenden en/of ontvangen van beeld- en/of geluidssignalen). |
| Inwinningscriteria | Een telecommunicatietoren of zendtoren die niet voldoet aan de opnamecriteria voor gebouwen, wordt aangegeven als een inrichtingselement van het type zendmast.<br>Zend – en/of ontvangstmasten hoger dan 15 meter, al dan niet op een gebouw (de mast moet 15 meter zijn), worden opgenomen. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **zichtbaar wrak** |
| Definitie | Wrak van vergaan schip dat (deels) boven water uitsteekt. |
| Inwinningscriteria | Wordt niet ingewonnen. |
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |

| Domein | IE\_typeInrichtingselement |
|:---|:---|
| Domeinwaarde | **overig** |
| Definitie | Het type inrichtingselement is bekend, maar anders dan de genoemde waarden. |
| Inwinningscriteria | Bijvoorbeeld een belvédère (punt met fraai uitzicht), observatiepunt of een doolhof. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

### Attribuut hoogte

| Attribuut | hoogte |
|:---|:---|
| Definitie | De hoogte van het object (t.o.v. het maaiveld of t.o.v. NAP). |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Getal |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

### Attribuut breedte

| Attribuut | breedte |
|:---|:---|
| Definitie | De breedte van het object gemeten in meters. |
| Inwinningscriteria | Dit attribuut geldt alleen voor inrichtingselementen van het type 'strekdam, krib, golfbreker'. |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Geheel getal |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

### Attribuut soortnaam

| Attribuut | soortnaam |
|:---|:---|
| Definitie | Nadere specificatie van het type inrichtingselement. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

### Attribuut naam

| Attribuut | naam |
|:---|:---|
| Definitie | De naam van het inrichtingselement. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

### Attribuut nummer

| Attribuut | nummer |
|:---|:---|
| Definitie | Het nummer van het inrichtingselement. |
| Inwinningscriteria | Bijvoorbeeld het nummer van een grenspunt, kilometerpaal, kilometerpaal spoorweg, kilometerpaal water, kilometerraaibord, kilometerraaipaal, paal of strandpaal. |
| Volledigheid | Beperkt |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

### Attribuut hoogteniveau

| Attribuut | hoogteniveau |
|:---|:---|
| Definitie | Met het hoogteniveau wordt de relatieve hoogte van het geo-object weergegeven. Zo kan worden bepaald op welke wijze geo-objecten elkaar kruisen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Geheel getal |
| Domein | ≤ 0 (0, -1, -2, -3, …) |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

## 7.12 Objectklasse: plaats

_Definitie:_

Geografisch gebied gekenmerkt door een concentratie van gebouwen gebruikt voor wonen en werken.

_Inwinningscriteria:_

De objectklasse plaats bestaat uit de topografische bebouwde kommen en hun onderverdelingen.

Een topografische bebouwde kom is een plaatsvlak dat, gebaseerd op de locatie van de plaatsnaamborden langs de toegangswegen, de kern van de bebouwing van een plaats omvat, alsmede de daarbij behorende ruimtegebruiksfuncties (zoals wegen, volkstuinen, sportterreinen, begraafplaatsen en bedrijventerreinen), en is afgebakend volgens zichtbare topografische grenslijnen in het landschap (zoals een sloot, de bosrand of de berm van een weg). Het vlak is voorzien van een typering, de naam of namen van de plaats, het aantal inwoners binnen het vlak, en de status van de plaats als bebouwde kom voor de Wegenverkeerswet en als woonplaats in de Basisregistratie Adressen en Gebouwen (BAG).

De volgende topografische elementen maken deel uit van het vlak van een topografische bebouwde kom:

- Alle aaneengesloten bebouwing inclusief erven. Bebouwing buiten een bebouwingskern die alleen bereikbaar is vanuit de bebouwde kom en waar niet met plaatsnaamborden is aangegeven dat de bebouwing buiten de bebouwde kom ligt, alsmede bedrijventerreinen aan de rand van een plaats vallen ook binnen het vlak.

- Alle wegen tussen de bebouwing, met uitzondering van doorgaande wegen zonder erftoegangen die doorlopen buiten de bebouwingskern, vanaf de laatste kruising met een andere weg met erftoegangen binnen de bebouwingskern.

- Alle wegen aan de rand van de bebouwing die vallen binnen de bebouwde kom volgens de Wegenverkeerswet, met uitzondering van doorgaande wegen zoals hierboven beschreven.

- Alle plantsoenen en parken tussen en aan de rand van de bebouwing.

- Alle waterlopen tussen de bebouwing, met uitzondering van waterlopen die doorlopen buiten de bebouwingskern en breder zijn dan zes meter ter hoogte van de buitenrand van de bebouwingskern, vanaf de laatste kruising met een brug of een tunnel binnen de bebouwingskern.

- Alle sportterreinen en trapveldjes die tussen of aan de rand van de bebouwing gelegen zijn, met uitzondering van buiten de bebouwingskern gelegen golfterreinen.

- Alle begraafplaatsen die tussen of aan de rand van de bebouwing gelegen zijn.

- Alle volkstuinen die tussen of aan de rand van de bebouwing gelegen zijn.

- Alle terreinen tussen of aan de rand van de bebouwing waarop een van de bovenstaande elementen wordt aangelegd of ontwikkeld, zoals nieuwbouwwijken of bedrijventerreinen in aanleg.

- Alle andere topografische elementen die omsloten worden door een van de bovenstaande elementen, met uitzondering van landbouwgebied.

- De plaatsvlakken van type buurtschap volgen bovenstaande regels niet. Hun vlakgrens is zo bepaald, dat in ieder geval alle bebouwing die tot het buurtschap behoort binnen het vlak valt. Voor het overige houdt de begrenzing van de buurtschappen weinig rekening met de onderliggende topografie en is daarmee veel minder nauwkeurig dan die van de andere topografische bebouwde kommen. Dit past bij het 'vage' karakter van de meeste buurtschapgrenzen en is vergelijkbaar met de begrenzing van veel geografische gebieden. Een buurtschap overlapt echter niet met topografische bebouwde kommen van een ander type.

### Attribuut labelPunt

| Attribuut | labelPunt |
|:---|:---|
| Definitie | De puntgeometrie van een plaats object. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Point |
| Domein | "Ruimtelijke coördinaten" |
			

### Attribuut geometrieVlak

| Attribuut | geometrieVlak |
|:---|:---|

| Definitie | De vlakgeometrie van een plaats object. |

| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Surface of GM\_MultiSurface |
| Domein | "Ruimtelijke coördinaten" |


### Attribuut typeGebied

| Attribuut | typeGebied |
|:---|:---|
		 
| Definitie | Het soort gebied. |
																																																					 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "PL\_typeGebied" |
			

#### Domein "PL\_typeGebied"

| Domein | PL\_typeGebied |
|:---|:---|
| Domeinwaarde | **woonkern** |
| Definitie | Bebouwingskern met hoofdzakelijk een woonfunctie, die tevens een bebouwde kom voor de Wegenverkeerswet is. |
																																																			 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |
			

| Domein | PL\_typeGebied |
|:---|:---|
| Domeinwaarde | **industriekern** |
| Definitie | Bebouwingskern met hoofdzakelijk een bedrijfsmatige functie, zoals een bedrijventerrein, een haven of een vliegveld, voorzien van openbare wegen. |
		 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |
			

| Domein | PL\_typeGebied |
|:---|:---|
| Domeinwaarde | **recreatiekern** |
| Definitie | Bebouwingskern met hoofdzakelijk een (verblijfs)recreatieve functie, zoals een bungalowpark, voorzien van openbare wegen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | PL\_typeGebied |
|:---|:---|
| Domeinwaarde | **deelkern** |
| Definitie | Historische bebouwingskern, ruimtelijk te onderscheiden van de omliggende bebouwing, gelegen binnen een bebouwde kom voor de Wegenverkeerswet van een andere plaats. |
	 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
						 

| Domein | PL\_typeGebied |
|:---|:---|
| Domeinwaarde | **gehucht** |
| Definitie | Kleine bebouwingskern of concentratie van aaneengesloten bebouwing, niet zijnde lintbebouwing, die geen bebouwde kom voor de Wegenverkeerswet vormt. |

| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
					 

| Domein | PL\_typeGebied |
|:---|:---|
| Domeinwaarde | **buurtschap** |
| Definitie | Lintbebouwing of verspreid staande bebouwing in landelijk gebied met een zekere mate van sociale samenhang, die geen bebouwde kom voor de Wegenverkeerswet vormt. |
	 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
		 

| Domein | PL\_typeGebied |
|:---|:---|
| Domeinwaarde | **stadsdeel** |
| Definitie | Grote administratief-geografische eenheid binnen een stedelijke gemeente. |
| Inwinningscriteria | Wordt alleen ingewonnen als onderverdeling en binnen de begrenzing van een topografische bebouwde kom, indien de gemeente de plaats heeft ingedeeld in stadsdelen. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | PL\_typeGebied |
|:---|:---|
| Domeinwaarde | **wijk** |
| Definitie | Eenheid binnen een bebouwingskern die ruimtelijk min of meer een afgesloten geheel vormt. |
| Inwinningscriteria | Wordt alleen ingewonnen als onderverdeling en binnen de begrenzing van een topografische bebouwde kom.<br>De onderverdeling in wijken en buurten is gebaseerd op de topografische en sociaal-geografische indeling van de plaats en kan afwijken van de statistische indeling zoals weergegeven in de Wijk- en buurtindeling van het Centraal Bureau voor de Statistiek. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

| Domein | PL\_typeGebied |
|:---|:---|
| Domeinwaarde | **buurt** |
| Definitie | Kleine eenheid binnen een plaats, doorgaans met een zekere mate van sociale samenhang. |
| Inwinningscriteria | Wordt alleen ingewonnen als onderverdeling en binnen de begrenzing van een topografische bebouwde kom.<br>De onderverdeling in wijken en buurten is gebaseerd op de topografische en sociaal-geografische indeling van de plaats en kan afwijken van de statistische indeling zoals weergegeven in de Wijk- en buurtindeling van het Centraal Bureau voor de Statistiek. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut bebouwde kom

| Attribuut | bebouwde kom |
|:---|:---|
| Definitie | Aanduiding of het gebied de bebouwde kom van een plaats omvat. |
| Inwinningscriteria | De status van de bebouwingskern volgens de Wegenverkeerswet is bepalend. De aanwezigheid van plaatsnaamborden is hierbij een hulpmiddel. |
| Volledigheid | Volledig |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

#### Domein "PL\_isBebouwdeKom"

| Domein | 'PL\_isBebouwdeKom |
|:---|:---|
| Domeinwaarde | **ja** |
| Definitie | Het gebied omvat de bebouwde kom van een plaats. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |


| Domein | 'PL\_isBebouwdeKom |
|:---|:---|
| Domeinwaarde | **nee** |
| Definitie | Het gebied omvat niet de bebouwde kom van een plaats. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut isBAGwoonplaats

| Attribuut | isBAGwoonplaats |
|:---|:---|
| Definitie | Aanduiding of de naam afkomstig is uit de BAG. |
| Inwinningscriteria | Voor plaatsen die een eigen BAG-woonplaatsgebied hebben, wordt de spelling van de naam van het BAG-woonplaatsgebied overgenomen als officiële naam, met uitzondering van toevoegingen ter onderscheiding van gelijknamige plaatsen (bijvoorbeeld "Bergen L" voor "Bergen" in de provincie Limburg), afkortingen (bijvoorbeeld "St.-Annaparochie" voor "Sint-Annaparochie") en een kleine beginletter (bijvoorbeeld "de Lutte" voor "De Lutte"). |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "PL\_isBAGwoonplaats" |

#### Domein "PL\_isBAGwoonplaats"

| Domein | PL\_isBAGwoonplaats |
|:---|:---|
| Domeinwaarde | **ja** |
| Definitie | De naam is afkomstig uit de BAG. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
			

| Domein | PL\_isBAGwoonplaats |
|:---|:---|
| Domeinwaarde | **nee** |
| Definitie | De naam is niet afkomstig uit de BAG. |
					 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
	 

### Attribuut aantal inwoners

| Attribuut | aantal inwoners |
|:---|:---|
| Definitie | Het aantal inwoners dat in een plaats woont. |
| Inwinningscriteria | Het aantal inwoners van een topografische bebouwde kom is het totaal van alle mensen die als bewoner op een van de binnen het vlak gelegen adressen geregistreerd staan in de Basisregistratie Personen (BRP) op peildatum 1 juli van het jaar waarin de luchtfoto's genomen zijn, die gebruikt zijn voor het intekenen van de vlakken. Omdat voor de vlakbegrenzing de oever van een water als grens is aangehouden, waardoor woonboten langs een oever niet binnen een vlak vallen, is het inwoneraantal van het vlak vermeerderd met de mensen die als bewoner van een woonboot grenzend aan een vlak geregistreerd staan. Hiervoor is een buffer van 25 meter aangehouden gerekend vanaf de vlakgrens.<br>Bij deze telling moet opgemerkt dat niet alle in de BRP geregistreerde inwoners van Nederland gekoppeld zijn aan een adreslocatie. Het gaat echter om minder dan 0,1% van de in de BRP geregistreerde inwoners die niet bij de berekening wordt meegenomen.<br>De berekening en telling van het aantal inwoners van de topografische bebouwde kommen wordt uitgevoerd door het Centraal Bureau voor de Statistiek (CBS), dat toegang heeft tot de BRP-gegevens. |
| Volledigheid | Volledig |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Geheel getal |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut Naam Officieel

| Attribuut | Naam Officieel |
|:---|:---|
| Definitie | De officiële naam van de plaats. |
| Inwinningscriteria | De officiële naam zoals geregistreerd in de Basisregistratie Adressen en Gebouwen (BAG).<br>Voor plaatsen die een eigen BAG-woonplaatsgebied hebben, wordt de spelling van de naam van het BAG-woonplaatsgebied overgenomen als officiële naam, met uitzondering van toevoegingen ter onderscheiding van gelijknamige plaatsen (bijvoorbeeld "Bergen L" voor "Bergen" in de provincie Limburg), afkortingen (bijvoorbeeld "St.-Annaparochie" voor "Sint-Annaparochie") en een kleine beginletter (bijvoorbeeld "de Lutte" voor "De Lutte"). |
| Volledigheid | Volledig |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut naam (Nl)

| Attribuut | naam (Nl) |
|:---|:---|
| Definitie | De Nederlandse naam van de plaats. |
| Inwinningscriteria | De Nederlandse naam van een plaats wordt altijd ingewonnen, ook als dit niet de officiële naam is. |
| Volledigheid | Volledig |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut naam (Fr)

| Attribuut | naam (Fr) |
|:---|:---|
| Definitie | De Friese naam van de plaats. |
| Inwinningscriteria | Wordt alleen in Friesland ingewonnen. Voor plaatsen gelegen in het Fries taalgebied van de provincie Fryslân is zowel de Nederlandse als de Friese naam aangegeven. |
| Volledigheid | Volledig |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |

## 7.14 Objectklasse: plantopografie

_Definitie:_

ruimtelijk object at wel gepland is, maar nog niet in uitvoering is; meestal een groot infrastructureel object.

_Inwinningscriteria:_

\-

### Attribuut labelPunt

| Attribuut | labelPunt |
|:---|:---|
| Definitie | De puntgeometrie van een plantopografie object. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Point |
| Domein | "Ruimtelijke coördinaten" |
																							

### Attribuut geometrieLijn

| Attribuut | geometrieLijn |
|:---|:---|
| Definitie | De lijngeometrie van een plantopografie object. |
		 
	 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Curve |
| Domein | "Ruimtelijke coördinaten" |
			

### Attribuut geometrieVlak

						 
		 

| Attribuut | geometrieVlak |
|:---|:---|
| Definitie | De vlakgeometrie van een plantopografie object. |
	 
	
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Surface of GM\_MultiSurface |
| Domein | "Ruimtelijke coördinaten" |
						

### Attribuut typeObject

| Attribuut | typeObject |
|:---|:---|
| Definitie | Het soort plantopografie object. |
		 
	 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "PT\_typeObject" |
			

#### Domein "PT\_typeObject"

| Domein | PT\_typeObject |
|:---|:---|
| Domeinwaarde | **weg** |
| Definitie | Plantopografie van wegdelen. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

| Domein | PT\_typeObject |
|:---|:---|
| Domeinwaarde | **spoor** |
| Definitie | Plantopografie van spoorbaandelen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | PT\_typeObject |
|:---|:---|
| Domeinwaarde | **water** |
| Definitie | Plantopografie van waterdelen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | PT\_typeObject |
|:---|:---|
| Domeinwaarde | **overig** |
| Definitie | Plantopografie van overige objectklassen. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut naam

| Attribuut | naam |
|:---|:---|
| Definitie | De naam van het plan of van het geplande object. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

## 7.10 Objectklasse: registratief gebied

_Definitie:_

Op basis van wet- en regelgeving afgebakend gebied dat als eenheid geldt van politieke/bestuurlijke verantwoordelijkheid of voor bedrijfsvoering.

_Inwinningscriteria:_

De basis voor de grenzen in de BRT is het product TOPGrenzen geweest, dat tot 2014 is bijgehouden door de Topografische Dienst en Topografische Dienst Kadaster.
Vanaf 2014 is het muteren van de registratieve gebieden in de BRT gebaseerd op mutaties in de Basisregistratie Kadaster (BRK). In 2014 zijn de grootste verschillen geanalyseerd (afwijking > 40 meter), besproken met de BRK en zo nodig gecorrigeerd in de BRT.

De mutaties in de BRK worden in enigszins gegeneraliseerde vorm overgenomen in de BRT, waarbij een gemeentegrens in TOP10NL zo veel mogelijk de objecten in TOP10NL volgt.

Voor de 12-mijls zone zijn de "Grenzen territoriale zee" van de Dienst der Hydrografie de bron. Ook deze begrenzing is gegeneraliseerd opgenomen in de BRT.

### Attribuut geometrieVlak

| Attribuut | geometrieVlak |
|:---|:---|
| Definitie | De vlakgeometrie van een registratief gebied object. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | GM\_Surface of GM\_MultiSurface |
| Domein | "Ruimtelijke coördinaten" |

### Attribuut type registratief gebied

| Attribuut | type registratief gebied |
|:---|:---|
| Definitie | Het soort administratief gebied. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "RG\_typeRegistratiefGebied" |

#### Domein "RG\_typeRegistratiefGebied"

| Domein | RG\_typeRegistratiefGebied |
|:---|:---|
| Domeinwaarde | **land** |
| Definitie | Begrenzing van Nederland, begrenst door België, Duitsland en de 12-mijls zone. |
| Inwinningscriteria | Het land "Nederland" is een samenvoeging van alle provincies. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | RG\_typeRegistratiefGebied |
|:---|:---|
| Domeinwaarde | **provincie** |
| Definitie | Staatkundig onderdeel van Nederland. |
| Inwinningscriteria | De provincies zijn een samenvoeging van de gemeenten die behoren tot deze provincie. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | RG\_typeRegistratiefGebied |
|:---|:---|
| Domeinwaarde | **gemeente** |
| Definitie | Zelfstandig, zelfbestuur en autonomie bezittend onderdeel van de staat Nederland, onder het bestuur van een raad, een burgemeester en wethouders. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | RG\_typeRegistratiefGebied |
|:---|:---|
| Domeinwaarde | **territoriale zee** |
| Definitie | Een zeestrook, grenzend aan het landgebied van Nederland waarover de soevereiniteit van Nederland zich uitstrekt. |
| Inwinningscriteria | De territoriale zee is gebaseerd op de laagwaterlijn en de 12-mijls zone. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | RG\_typeRegistratiefGebied |
|:---|:---|
| Domeinwaarde | **waterschap** |
| Definitie | Lichaam dat, onder toezicht van de Provinciale Staten, in een bepaald gebied voor waterlozing en waterkering zorgt. |
| Inwinningscriteria | Wordt niet ingewonnen. |
| Volledigheid | Niet |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut NaamOfficieel

| Attribuut | NaamOfficieel |
|:---|:---|
| Definitie | De officiële naam van het registratief gebied. |
| Inwinningscriteria | Waar mogelijk wordt de officiële naam vastgelegd, waar niet mogelijk de Nederlandse en/of de Friese. |
| Volledigheid | Volledig |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut naam (Nl)

| Attribuut | naam (Nl) |
|:---|:---|
| Definitie | De Nederlandse naam van het registratief gebied. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut naam (Fr)

| Attribuut | naam (Fr) |
|:---|:---|
| Definitie | De Friese naam van het registratief gebied. |
| Inwinningscriteria | Wordt alleen in Friesland ingewonnen. |
| Volledigheid | Volledig |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut nummer

| Attribuut | nummer |
|:---|:---|
| Definitie | Het administratieve nummer van het registratief gebied. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

## 7.8 Objectklasse: reliëf

_Definitie:_

Object dat tot doel heeft hoogteverschillen in het landschap te representeren.

_Inwinningscriteria:_

"Talud, hoogteverschil" en "steile rand, aardrand" worden met twee lijnen opgeslagen: een lijn voor de hoge zijde en een lijn voor de lage zijde. De andere geo-objecten worden met een enkele lijn opgeslagen.

### Attribuut geometrieLijn

| Attribuut | geometrieLijn |
|:---|:---|
| Definitie | De lijngeometrie van een reliëf object. |
													
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Curve |
| Domein | "Ruimtelijke coördinaten" |
							

### Attribuut hogeZijde

| Attribuut | hogeZijde |
|:---|:---|
| Definitie | De lijngeometrie van de hoge zijde van een reliëf object. |
																																								 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Curve |
| Domein | "Ruimtelijke coördinaten" |
							

### Attribuut lageZijde

| Attribuut | lageZijde |
|:---|:---|
| Definitie | De lijngeometrie van de lage zijde van een reliëf object. |
																																 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Curve |
| Domein | "Ruimtelijke coördinaten" |
							

### Attribuut functie
				 
					 
					 

| Attribuut | functie |
|:---|:---|
| Definitie | Aanduiding of het object een geluidswerende functie heeft. |
																							 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
			
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Domein | "RE\_functie" |
							

#### Domein "RE\_functie"

| Domein | RE\_functie |
|:---|:---|
| Domeinwaarde | **geluid weren** |
| Definitie | Het reliëf heeft de functie van geluidswering in de vorm van een langwerpige, opgeworpen hoogte. |
| Inwinningscriteria | Minimum lengte: 100 meter. Minimum hoogte: 2 meter.<br>Een dijk met daarop een geluidsscherm wordt aangegeven als dijk/… (zonder de functie "geluid weren") in combinatie met een inrichtingslijn geluidswering.<br>Een wal met daarop een geluidsscherm wordt aangegeven als een inrichtingslijn geluidswering. |
						 
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |
							
### Attribuut hoogteklasse
				 
							 
						

| Attribuut | hoogteklasse |
|:---|:---|
| Definitie | Klasse van de hoogte van een object ten opzichte van het maaiveld. |
												 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
			
| Optionaliteit | Verplicht |
| Formaat | Getal |
| Domein | "RE\_hoogteklasse" |
							

#### Domein "RE\_hoogteklasse"
				 

| Domein | RE\_hoogteklasse |
|:---|:---|
| Domeinwaarde | **< 1 meter** |
| Definitie | De hoogte van een wal, talud of steile rand is lager dan 1 meter. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |
							

| Domein | RE\_hoogteklasse |
|:---|:---|
| Domeinwaarde | **1 - 2,5 meter** |
| Definitie | De hoogte van het object ten opzichte van het maaiveld ligt tussen 1 en 2,5 meter. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |
							

| Domein | RE\_hoogteklasse |
|:---|:---|
| Domeinwaarde | **> 2,5 meter** |
| Definitie | De hoogte van het object ten opzichte van het maaiveld is groter dan 2,5 meter. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |


### Attribuut type reliëf

| Attribuut | type reliëf |
|:---|:---|
| Definitie | Het soort reliëf. |
																																 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "RE\_typeReliëf" |
							
#### Domein "RE\_typeReliëf"
				 
| Domein | RE\_typeReliëf |
|:---|:---|
| Domeinwaarde | **wal** |
| Definitie | Langgerekte ophoging in het terrein met een hoogte tussen 0,50 en 1,00 meter. |
| Inwinningscriteria | Minimumlengte: 100 meter.<br>Een calamiteitenkering (een dijk als kering van vloeistoffen om bijvoorbeeld een tankpark) wordt ongeacht de hoogte als 'wal' opgenomen.<br>Indien er een weg over de wal loopt, dan wordt de wal niet opgenomen.<br>Een wal om een waterbak en mestopslag worden niet opgenomen.<br>De omdijking om een vloeiveld (omdijkt stuk land, bestemd voor bezinking van afvalwater) wordt altijd als wal opgenomen.<br>Kades worden niet ingewonnen.<br>Een wal met geluidsscherm, samen lager dan 2 meter, wordt ingewonnen als 'wal'. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | RE\_typeReliëf |
|:---|:---|
| Domeinwaarde | **talud, hoogteverschil** |
| Definitie | Plaatselijk glooiende terreinverheffing of -inzinking (hoogteverschil). / Schuinte van het zijvlak van aardwerken, dijken, spoorbanen, vestingwerken, etc. (talud). |
| Inwinningscriteria | Grotere terreinglooiingen worden opgenomen als hoogtelijnen.<br>Van een dijk wordt elke zijde opgenomen als een talud, hoogteverschil.<br>De onderzijde en de bovenzijde van het talud worden opgenomen.<br>Minimale lengte in geval van een dijk: 100 meter.<br>Minimale hoogteverschil tussen twee maaivelden: 1 meter (als geluidswering 2 meter).<br>Minimum hoogteverschil tussen maaiveld en water: 3 meter.<br>Wordt niet opgenomen in duingebieden en bij basaltblokken/steenglooiing.<br>Indien er een weg op een dijk loopt, dan worden hoge taludlijnen van deze dijk geplaatst op de kant van het wegdeel indien de afstand tussen de bovenzijde van het talud en de wegkant kleiner is dan 6 meter.<br>Een calamiteitenkering (dijk als kering van vloeistoffen om bijvoorbeeld een tankpark) wordt altijd als kade, wal opgenomen, ongeacht de hoogte. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | RE\_typeReliëf |
|:---|:---|
| Domeinwaarde | **steile rand, aardrand** |
| Definitie | Plotselinge terreinverheffing of inzinking. |
| Inwinningscriteria | Minimumlengte 100 meter.<br>Minimum hoogteverschil tussen twee maaivelden: 1 meter.<br>Minimum hoogteverschil tussen maaiveld en water: 3 meter. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |


### Attribuut hoogteniveau

| Attribuut | hoogteniveau |
|:---|:---|
| Definitie | Het hoogteniveau van het object |
														 
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Geheel getal |
| Domein | ≤ 0 (0, -1, -2, -3, …) |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

## 7.3 Objectklasse: spoorbaandeel

_Definitie:_

Kleinste functioneel onafhankelijk stukje spoorbaan met gelijkblijvende, homogene eigenschappen en relaties dat er binnen een spoorwegnet wordt onderscheiden.

_Inwinningscriteria:_

De hartlijnen worden opgenomen. Op het rangeergedeelte van een emplacement worden de buitenste sporen op de juiste plaats aangegeven, waarna de ruimte tussen het doorgaande spoor en het buitenste spoor wordt opgevuld met spoorbaandelen zonder wissels (kruisingen).

### Attribuut geometriePunt

| Attribuut | geometriePunt |
|:---|:---|
| Definitie | De puntgeometrie van een spoorbaandeel object. |
		 
		 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Point |
| Domein | "Ruimtelijke coördinaten" |
			

### Attribuut geometrieLijn

| Attribuut | geometrieLijn |
|:---|:---|
| Definitie | De lijngeometrie van een spoorbaandeel object. |
						 
																																			 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Curve |
| Domein | "Ruimtelijke coördinaten" |
			

### Attribuut aantal sporen

| Attribuut | aantal sporen |
|:---|:---|
| Definitie | Het aantal sporen van het spoorbaandeel. |
| Inwinningscriteria | Een wisselend aantal sporen wordt pas weergegeven als het aantal sporen over tenminste 5 kilometer constant is. Indien het aantal sporen over een lengte van minder dan 5 km wisselt, wordt het extra spoor niet apart weergegeven. Een tijdelijk parallel spoor op een volledig eigen tracé, wordt apart weergegeven.<br>Echter: de minimum lengte voor opname van een dubbelsporig gedeelte in een **enkelspoor** is 500 meter en ditzelfde geld voor een enkelsporig gedeelte in een **dubbelspoor**.<br>Voor het inwinnen van het aantal sporen van een spoorbaandeel is gebruik gemaakt van gegevens van ProRail. |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "SP\_aantalSporen" |
		 
		 
						 

#### Domein "SP\_aantalSporen"

| Domein | SP\_ aantalSporen |
|:---|:---|
| Domeinwaarde | **enkel** |
| Definitie | Spoorbaan bestaande uit één spoor. |
							
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
								

| Domein | SP\_ aantalSporen |
|:---|:---|
| Domeinwaarde | **dubbel** |
| Definitie | Spoorbaan bestaande uit twee sporen. |
			
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
		 

| Domein | SP\_ aantalSporen |
|:---|:---|
| Domeinwaarde | **meervoudig** |
| Definitie | Spoorbaan bestaande uit meer dan twee sporen. |
					
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
### Attribuut fysiek voorkomen
				 
							 
						 

| Attribuut | fysiek voorkomen |
|:---|:---|
| Definitie | De plaats waar het object zich bevindt t.o.v. andere constructies. |
						 
						 
| Inwinningscriteria | - |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Domein | "SP\_fysiekVoorkomen" |


#### Domein "SP\_fysiekVoorkomen"

| Domein | SP\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **op vast deel van brug** |
| Definitie | Gelegen op een niet beweegbaar deel van een kunstwerk dat een verbinding vormt door middel van een overspanning. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
	

| Domein | SP\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **op beweegbaar deel van brug** |
| Definitie | Gelegen op een beweegbaar deel van een kunstwerk dat een verbinding vormt door middel van een overspanning. |
								
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
			

| Domein | SP\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **overkluisd** |
| Definitie | Overbouwd door bebouwing of door een al dan niet licht doorlatend dak, zodanig dat de orthogonale projectie van de bebouwing of het dak op of over het object valt. |
| Inwinningscriteria | Het verloop van het object onder de bebouwing, wordt volgens de meest waarschijnlijke vorm aangegeven. Een overkluizing is geen aanleiding tot verandering van het hoogteniveau (bijvoorbeeld: een object waarboven zich alleen een gebouw bevindt, heeft als hoogteniveau de attribuutwaarde 0). |
		 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
					

| Domein | SP\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **in tunnel** |
| Definitie | Gelegen in een kunstmatig aangelegde, onderaardse of door een berg geboorde kokervormige doorgang. |
									
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
						 

### Attribuut spoorbreedte

| Attribuut | spoorbreedte |
|:---|:---|
| Definitie | De breedteklasse van het spoor. |

									
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "SP\_spoorbreedte" |
					

#### Domein "SP\_spoorbreedte"

| Domein | SP\_spoorbreedte |
|:---|:---|
| Domeinwaarde | **normaalspoor** |
| Definitie | Spoor met een normale breedte, namelijk 1,435 meter. |
		 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
					

| Domein | SP\_spoorbreedte |
|:---|:---|
| Domeinwaarde | **smalspoor** |
| Definitie | Spoorbaandeel met een geringere breedte dan normaalspoor. |
| Inwinningscriteria | Wordt alleen weergegeven in open terrein. |
									
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

### Attribuut type infrastructuur
				 
							 
						 

| Attribuut | type infrastructuur |
|:---|:---|
| Definitie | Aanduiding of het object een verbinding of een kruising is. |
						 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "SP\_typeInfrastructuur" |
							


#### Domein "SP\_typeInfrastructuur"

| Domein | SP\_typeInfrastructuur |
|:---|:---|
| Domeinwaarde | **verbinding** |
| Definitie | Object waar maximaal twee objecten van hetzelfde objecttype op aansluiten. |
			
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |
							


| Domein | SP\_typeInfrastructuur |
|:---|:---|
| Domeinwaarde | **kruising** |
| Definitie | Een object waar drie of meer objecten van hetzelfde objecttype op aansluiten. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |


### Attribuut type spoorbaan

| Attribuut | type spoorbaan |
|:---|:---|
| Definitie | Het soort vervoermiddel waarvoor het spoorbaandeel bestemd is. |
						 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "SP\_typeSpoorbaan" |


#### Domein "SP\_typeSpoorbaan"

| Domein | SP\_typeSpoorbaan |
|:---|:---|
| Domeinwaarde | **trein** |
| Definitie | Spoorbaandeel bestemd voor railvoertuig voor de langere afstand dat sneller dan 45 km per uur kan, bestaande uit een enkele of een reeks van locomotieven, treinstellen en/of wagons. |
			
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |


| Domein | SP\_typeSpoorbaan |
|:---|:---|
| Domeinwaarde | **tram** |
| Definitie | Spoorbaandeel bestemd voor railvoertuig ten behoeve van personenvervoer over korte afstand, niet harder rijdend dan 45 km per uur. |
| Inwinningscriteria | Kan zowel enkel- als meersporig voorkomen. Hierbij geldt geen minimummaat voor opname.<br>Indien de tramroute loopt over een brug, door een tunnel of overkluisd is wordt dit voor het betreffende routedeel als attribuut toegevoegd. |
					
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |


| Domein | SP\_typeSpoorbaan |
|:---|:---|
| Domeinwaarde | **sneltram** |
| Definitie | Spoorbaandeel bestemd voor railvoertuig ten behoeve van personenvervoer over korte afstand, harder rijdend dan 45 km per uur. |
| Inwinningscriteria | Kan zowel enkel- als meersporig voorkomen. Hierbij geldt geen minimummaat voor opname.<br>Indien de tramroute loopt over een brug, door een tunnel of overkluisd is wordt dit voor het betreffende routedeel als attribuut toegevoegd.<br>Indien op een tracé zowel tram als sneltram rijdt wordt het tracé gegeven als sneltram. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
			

| Domein | SP\_typeSpoorbaan |
|:---|:---|
| Domeinwaarde | **metro** |
| Definitie | Spoorbaandeel bestemd voor al dan niet ondergrondse personentrein in een grote stad. |
| Inwinningscriteria | Wordt niet voorzien van kilometrering en het ondergrondse deel krijgt geen spoorbaanlichaam. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
			

| Domein | SP\_typeSpoorbaan |
|:---|:---|
| Domeinwaarde | **gemengd** |
| Definitie | Spoorbaandeel bestemd voor een combinatie van zowel trein, metro, sneltram of tramverkeer. |
																			 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
			
### Attribuut vervoerfunctie

| Attribuut | vervoerfunctie |
|:---|:---|
| Definitie | De functie waarvoor het spoor gebruikt wordt. |
																		 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "SP\_vervoerFunctie" |
							

#### Domein "SP\_vervoerFunctie"

| Domein | SP\_vervoerFunctie |
|:---|:---|
| Domeinwaarde | **gemengd gebruik** |
| Definitie | Spoorbaan, zowel bestemd voor personen- als goederenvervoer. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
							

| Domein | SP\_vervoerFunctie |
|:---|:---|
| Domeinwaarde | **personenvervoer** |
| Definitie | Spoorbaan, alleen bestemd voor personenvervoer. |
	 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
					

| Domein | SP\_vervoerFunctie |
|:---|:---|
| Domeinwaarde | **goederenvervoer** |
| Definitie | Spoorbaan, alleen bestemd voor goederenvervoer. |
									
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
						 

| Domein | SP\_vervoerFunctie |
|:---|:---|
| Domeinwaarde | **museumlijn** |
| Definitie | Spoorbaan, enkel in gebruik als toeristische attractie. |
							
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
	 

### Attribuut elektrificatie

| Attribuut | elektrificatie |
|:---|:---|
| Definitie | Aanduiding of het spoorbaandeel geëlektrificeerd is of niet. |
			
			
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "SP\_elektrificatie" |
	 

#### Domein "SP\_elektrificatie"

| Domein | SP\_elektrificatie |
|:---|:---|
| Domeinwaarde | **ja** |
| Definitie | Attribuut waarmee wordt aangegeven dat een spoorbaan geëlektrificeerd is. |
			
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |


| Domein | SP\_elektrificatie |
|:---|:---|
| Domeinwaarde | **nee** |
| Definitie | Attribuut waarmee wordt aangegeven dat een niet spoorbaan geëlektrificeerd is. |

| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |


### Attribuut brugnaam

| Attribuut | brugnaam |
|:---|:---|
| Definitie | De naam van een spoorbrug. |
					
			
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

### Attribuut tunnelnaam

| Attribuut | tunnelnaam |
|:---|:---|
			
| Definitie | Naam van een spoortunnel. |
			
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

### Attribuut baanvaknaam

| Attribuut | baanvaknaam |
|:---|:---|
| Definitie | De naam van het baanvak waarin het spoorbaandeel zich bevind. |
| Inwinningscriteria | Wordt niet ingewonnen. |
| Volledigheid | Niet |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

### Attribuut status

| Attribuut | status |
|:---|:---|
| Definitie | De staat waarin het object zich bevindt. |
							

| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "Status" |
						 

### Attribuut hoogteniveau

| Attribuut | hoogteniveau |
|:---|:---|
| Definitie | Het hoogteniveau van het object. |
									

| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Geheel getal |
| Domein | ≤ 0 (0, -1, -2, -3, …) |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |

## 7.6 Objectklasse: terrein

_Definitie:_

Zichtbaar begrensd stuk grond, niet zijnde een van de andere opdelende ruimtelijke objecten (wegdeel of waterdeel).

_Inwinningscriteria:_

Voor terreinen begrensd door uitsluitend harde topografie (zoals wegdelen, spoorbaandelen, waterdelen en enkele inrichtingselementen) geldt geen minimummaat. Voor terreinen niet geheel begrensd door harde topografie is de minimumoppervlakte 1000 m². Voor eilanden (land omgeven door water): minimumoppervlakte 50 m².

Een berm smaller dan 6 meter en zonder talud en zonder brede houtrand wordt niet als terrein opgenomen als de berm begrensd wordt door een waterloop, bebouwing, bebouwd oppervlak of een weg. Een berm met talud wordt ongeacht de breedte als terrein met reliëf opgenomen. Het niet berijdbare middenvlak van een rotonde wordt, ongeacht de grootte, aangegeven.

Voor het bijhouden van het attribuut type_landgebruik wordt gebruik gemaakt van een externe bron. Voor agrarische percelen wordt hiervoor gebruik gemaakt van de Basisregistratie Gewaspercelen (BRP) van RVO. Het soort gewas dat een perceeleigenaar opgeeft in de BRP is bepalend voor het invullen van het juiste type_landgebruik in TOP10NL.

### Attribuut geometrieVlak

| Attribuut | geometrieVlak |
|:---|:---|
| Definitie | De vlakgeometrie van een terrein object. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | GM\_Surface |
| Domein | "Ruimtelijke coördinaten" |

### Attribuut fysiek voorkomen

| Attribuut | fysiek voorkomen |
|:---|:---|
| Definitie | De plaats waar het object zich bevindt t.o.v. andere constructies. |
| Inwinningscriteria | |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Domein | "TE\_fysiekvoorkomen" |

#### Domein "TE\_fysiekVoorkomen"

| Domein | TE\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **overkluisd** |
| Definitie | Overbouwd door bebouwing of door een al dan niet licht doorlatend dak, zodanig dat de orthogonale projectie van de bebouwing of het dak op of over het object valt. |
| Inwinningscriteria | Overkluizing wordt niet aangeven in het geval van kleine oversteekjes. Minimale oppervlakte overkluisd terrein: 100 m². |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **in tunnel** |
| Definitie | Gelegen in een kunstmatig aangelegde, onderaardse of door een berg geboorde kokervormige doorgang. |
| Inwinningscriteria | Een op zichzelf staande veetunnel breder dan 2 m wordt gegeven door het aanbrengen van een vlak overig in tunnel. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **op vast deel van brug** |
| Definitie | Object gelegen op een vast deel van een kunstwerk dat een verbinding vormt door middel van een overspanning. |
| Inwinningscriteria | Een losse brug die direct vanaf de weg toegang geeft tot bebouwing, een landerij, etc. én geen relatie heeft met een **weg** wordt niet gegeven. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **op beweegbaar deel van brug** |
| Definitie | Object gelegen op een beweegbaar deel van een kunstwerk dat een verbinding vormt door middel van een overspanning. |
| Inwinningscriteria | Een losse brug die direct vanaf de weg toegang geeft tot bebouwing, een landerij, etc. én geen relatie heeft met een **weg** wordt niet gegeven. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut type landgebruik

| Attribuut | type landgebruik |
|:---|:---|
| Definitie | De gebruiksbestemming van het terrein. |
| Inwinningscriteria | Indien er in het terrein meerdere vormen van begroeiing naast elkaar voorkomen, zonder dat daartussen duidelijke grenzen zijn aan te geven, dan wordt de meest voorkomende begroeiingsvorm opgenomen. Zo mogelijk worden binnen dit vlakobject kleinere vlakobjecten aangegeven met andere begroeiingsvormen, mits deze groter zijn dan plm. 1000 m². De perceeltjes behoren een globale indruk te geven van de bezettingsgraad van elk der vegetatievormen / vormen van grondgebruik. |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "TE\_typelandgebruik" |

#### Domein "TE\_typeIandgebruik"

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **aanlegsteiger** |
| Definitie | In het water uitstekende brug of pier, breder dan 2 meter, gebruikt om personen en goederen aan wal te brengen. |
| Inwinningscriteria | Minimum lengte 50 meter. Wordt gegeneraliseerd weergegeven.<br>De minimumlengte geldt niet indien de aanlegsteiger is gelegen in een waterdeel met de functie haven. Een rij onderling verbonden meerpalen wordt aangegeven als aanlegsteiger. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **akkerland** |
| Definitie | Terrein waar landbouwproducten worden verbouwd. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **basaltblokken, steenglooiing** |
| Definitie | Dijkversteviging m.b.v. stenen, tegels, basaltblokken, stortsteen (geen asfalt of bitumen) of een golfslagbreker, stroombreker of strekdam langs de kust en in rivieren. |
| Inwinningscriteria | Minimumgrootte: 50 m². Wordt niet opgenomen langs een kanaal. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **bebouwd gebied** |
| Definitie | Een oppervlak, (vrij) intensief gebruikt voor bewoning en/of productie en/of verhandeling van goederen en diensten, plus bijbehorend erf, wegen en openbaar groen (m.u.v. een plantsoen of park). |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **boomgaard** |
| Definitie | Terrein met hoogstammige fruitbomen. |
| Inwinningscriteria | Fruitbomen als onderdeel van een moestuin worden niet opgenomen. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **boomkwekerij** |
| Definitie | Terrein, overwegend in gebruik t.b.v. het opkweken van bomen (inclusief coniferen en sparren) en struiken, waarbij de hoogte van de aanplant niet van belang is. |
| Inwinningscriteria | Het terreingedeelte met plantgoed van een tuincentrum wordt ook opgenomen als boomkwekerij. Een verwaarloosde kerstsparkwekerij wordt weergegeven als bos: naaldbos. De wegen op de boomkwekerij worden gegeneraliseerd weergegeven. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **bos: gemengd bos** |
| Definitie | Oppervlak begroeid met een dusdanige aantal naald- en loofbomen dat de kruinen een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen. |
| Inwinningscriteria | Maximum percentage naaldbomen: 90%. Maximumpercentage loofbomen: 90%. Bij deze percentages worden het eventueel aanwezige onderhout en smalle stroken loof- en of naaldbos gelegen naast of als uitloper van het bos buiten beschouwing gelaten.<br>Minimumoppervlakte voor het logisch geheel van bospartijen op erven en in bebouwd gebied: 1000 m².<br>Minimumlengte en -breedte voor een brede houtrand: 50 meter resp. 3 meter.<br>Minimumoppervlakte in overige gevallen: 50 m².<br>Een afgebrand bos, kapvlakte, jonge aanplant of bosopslag (spontaan groeiend bos waarvan de begrenzing niet duidelijk kan worden onderscheiden) wordt behandeld als bos.<br>Een smalle strook loof- en/of naaldhout gelegen naast of als uitloper van een bos wordt geacht tot dit bos te behoren.<br>In een groot deel van de bossen worden bospaden ontoegankelijk gemaakt t.b.v. het wild door er greppels te graven, er bomen/takken neer te leggen of zandbergen op te werpen. Deze paden worden bij het bos getrokken.<br>Een heg op een wal (houtwal) wordt niet als inrichtingselement van het type 'heg, haag' ingewonnen, maar als bos (geen griend). |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **bos: griend** |
| Definitie | In of aan het water gelegen terrein, begroeid met laagafgeknot wilgenhout t.b.v. de productie van rijshout. |
| Inwinningscriteria | Verwilderd griend wordt opgenomen als loofbos. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **bos: loofbos** |
| Definitie | Oppervlak begroeid met een dusdanige aantal loofbomen dat de kruinen een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen. |
| Inwinningscriteria | Minimumpercentage loofbomen: 90%. Bij dit percentage worden het eventueel aanwezige onderhout en smalle stroken loof- en of naaldbos gelegen naast of als uitloper van het bos buiten beschouwing gelaten.<br>Minimumoppervlakte voor het logisch geheel van bospartijen op erven en in bebouwd gebied: 1000 m².<br>Minimumlengte en -breedte voor een brede houtrand: 50 meter resp. 3 meter.<br>Minimumoppervlakte in overige gevallen: 50 m².<br>Een afgebrand bos, kapvlakte, jonge aanplant of bosopslag (spontaan groeiend bos waarvan de begrenzing niet duidelijk kan worden onderscheiden) wordt behandeld als bos.<br>Een smalle strook loof- en/of naaldhout gelegen naast of als uitloper van een bos wordt geacht tot dit bos te behoren.<br>In een groot deel van de bossen worden bospaden ontoegankelijk gemaakt t.b.v. het wild door er greppels te graven, er bomen/takken neer te leggen of zandbergen op te werpen. Deze paden worden bij het bos getrokken.<br>Een heg op een wal (houtwal) wordt niet als inrichtingselement van het type 'heg, haag' ingewonnen, maar als bos (geen griend).<br>Een terrein, volgens een regelmatig patroon beplant met populieren zonder een ondergrond van gras wordt opgenomen als loofbos. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **bos: naaldbos** |
| Definitie | Oppervlak begroeid met een dusdanige aantal naaldbomen dat de kruinen een min of meer gesloten geheel vormen of, na volgroeiing van de bomen, zullen vormen. |
| Inwinningscriteria | Minimum percentage naaldbomen: 90%. Bij dit percentage worden het eventueel aanwezige onderhout en smalle stroken loof- en of naaldbos gelegen naast of als uitloper van het bos buiten beschouwing gelaten.<br>Minimumoppervlakte voor het logisch geheel van bospartijen op erven en in bebouwd gebied: 1000 m².<br>Minimumlengte en -breedte voor een brede houtrand: 50 meter resp. 3 meter.<br>Minimumoppervlakte in overige gevallen: 50 m².<br>Een afgebrand bos, kapvlakte, jonge aanplant of bosopslag (spontaan groeiend bos waarvan de begrenzing niet duidelijk kan worden onderscheiden) wordt behandeld als bos.<br>Een smalle strook loof- en/of naaldhout gelegen naast of als uitloper van een bos wordt geacht tot dit bos te behoren.<br>In een groot deel van de bossen worden bospaden ontoegankelijk gemaakt t.b.v. het wild door er greppels te graven, er bomen/takken neer te leggen of zandbergen op te werpen. Deze paden worden bij het bos getrokken.<br>Een heg op een wal (houtwal) wordt niet als inrichtingselement van het type 'heg, haag' ingewonnen, maar als bos (geen griend). |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **braakliggend** |
| Definitie | Een stuk grond dat geen functie vervult of niet wordt onderhouden, met uitzondering van landbouwgrond. |
| Inwinningscriteria | Braakliggende landbouwgronden en landbouwterreinen die zijn ingezaaid met groenbemesters worden aangegeven als braakliggend. Betreft het een andersoortig terrein dan wordt dit gegeven met een vlak van het type 'overig'. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **dodenakker** |
| Definitie | Terrein, gedeelte van een begraafplaats waar doden zijn of zullen worden begraven, niet gelegen in bos. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **dodenakker met bos** |
| Definitie | Terrein, gedeelte van een begraafplaats waar doden zijn of zullen worden begraven, gelegen in bos. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **duin** |
| Definitie | Terrein met grondsoort zand, langs de kust als natuurlijke kustverdediging, eventueel begroeid met helmgras of lage struiken. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **fruitkwekerij** |
| Definitie | Terrein met laagstammige fruitbomen en struiken waarvan de vruchten worden geoogst (zoals: rozenbottels, bessen, frambozen, druiven, etc.). |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **grasland** |
| Definitie | Terrein, overwegend begroeid met een grasachtige vegetatie. |
| Inwinningscriteria | Een graszaadkwekerij en graszodenbedrijf worden ook als grasland ingewonnen. Een (sier)gazon, d.w.z. een goed onderhouden grasperk, op een erf wordt opgenomen als terrein met het type landgebruik 'overig'.<br>Indien het grasland tijdelijk onder water is gezet worden de wallen en het water genegeerd.<br>Ook een smalle strook grasland, niet zijnde een berm en begrensd door harde topografie, wordt ingewonnen.<br>Indien de strook gras gelegen is langs een waterdeel en begrensd wordt door een bosrand dan geldt er een minimum breedtemaat van 2 meter vanaf insteek sloot.<br>Indien de strook gras gelegen is langs een waterdeel en begrensd wordt door zachte topografie dan geldt er een minimum breedtemaat van 6 meter vanaf kant water.<br>Indien de strook gras niet gelegen is langs een waterdeel en permanent aanwezig, dan wordt deze gegeven indien breder dan 6 meter.<br>Een grasland met bomen kan op verschillende manieren ingewonnen worden in TOP10NL.<br>- Bij één enkele rij bomen: als terrein grasland met een inrichtingselement bomenrij<br>- Bij meerdere rijen populieren: als terrein populieren<br>- In alle overige gevallen: als terrein loofbos. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **heide** |
| Definitie | Terrein, overwegend begroeid met heidevegetatie en wilde grassoorten. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **populieren** |
| Definitie | Terrein, volgens een regelmatig patroon beplant met populieren. |
| Inwinningscriteria | Het perceel wordt aangegeven als terrein van het type landgebruik populieren, indien de ondergrond bestaat uit grasland en het perceel is beplant met meerdere rijen populieren. Betreft het een enkele rij populieren dan wordt het terrein gegeven als grasland in combinatie met een inrichtingselement bomenrij.<br>In alle overige gevallen wordt het perceel aangegeven als "bos/ loofbos". |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **spoorbaanlichaam** |
| Definitie | Geheel van rails, dwarsliggers e.d. waarover de trein, metro of sneltram rijdt. |
| Inwinningscriteria | Het terrein loopt tot aan de begrenzende sloot, een hek of een vlak met ander landgebruik. Spoorbaanlichaam wordt ook aangegeven op een spoorbrug.<br>Spoorbaanlichamen worden ook aangegeven indien het spoor van het type trein is gelegen in tunnel. De breedte wordt bepaalt aan de hand van de in- en uitgangsbreedte van de tunnel.<br>Metro en sneltram in tunnel krijgen geen spoorbaanlichaam.<br>Spoorbaanlichaam wordt niet aangegeven als de spoorbaan geïntegreerd is in andere objecten en dus geen eigen grindbed heeft. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **zand** |
| Definitie | Terrein, grondsoort zand, van nature zonder enige begroeiing. |
| Inwinningscriteria | Bij een zandwinning of grindwinning wordt het terrein voor opslag van het zand of grind niet ingewonnen als 'zand'. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_typeIandgebruik |
|:---|:---|
| Domeinwaarde | **overig** |
| Definitie | De waarde van het objectkenmerk is bekend, maar anders dan de genoemde waarden. Een niet nader omschreven gebruiksbestemming. |
| Inwinningscriteria | Bijvoorbeeld een oppervlakte begroeid met struiken of varens, een dijkversteviging met asfalt of bitumen, onland (terrein zonder begroeiing of met onduidelijke begroeiing), een skibaan, een stortplaats, een terrein ingericht t.b.v. een tankstation, een terrein rondom een transformatorstation, tennisbanen, een tribune die geen geheel vormt met de bebouwing, een kunstgrasveld, een trottoir breder dan 6 meter, volkstuinen, een paardenbak of het drafgedeelte van een renbaan. Ook opgenomen wordt een (sier)gazon, d.w.z. een goed onderhouden grasperk, op een erf. Een mestopslag groter dan 1000 m² en het terrein met voor een nertsfarm specifieke bebouwing wordt ook opgenomen. Bij een weg in aanleg wordt het gerealiseerde gedeelte aangegeven als wegdeel. Voor de overige wegen in aanleg geldt dat het gedeelte van het terrein waar de werkzaamheden zijn aangevangen wordt aangegeven als een terrein met overig landgebruik. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |


### Attribuut voorkomen

| Attribuut | voorkomen |
|:---|:---|
| Definitie | Aanduiding dat er riet op het terrein voorkomt of dat het drassig/moerassig is. |
| Inwinningscriteria | - |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Domein | "TE\_voorkomen" |
							

#### Domein "TE\_voorkomen"
				 
					 
					 

| Domein | TE\_voorkomen |
|:---|:---|
| Domeinwaarde | **met riet** |
| Definitie | Met riet bedekt terreinoppervlak. |
| Inwinningscriteria | Minimum oppervlakte: 1000 m².<br>Rietkragen smaller dan 6 meter worden niet gegeven. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | TE\_voorkomen |
|:---|:---|
| Domeinwaarde | **dras, moerassig** |
| Definitie | Weke, moerassige grond. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut naam

| Attribuut | naam |
|:---|:---|
| Definitie | De naam van het terrein. |
| Inwinningscriteria | |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut hoogteniveau

| Attribuut | hoogteniveau |
|:---|:---|
| Definitie | Het hoogteniveau van het object. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Geheel getal |
| Domein | ≤ 0 (0, -1, -2, -3, …) |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

## 7.4 Objectklasse: waterdeel

_Definitie:_

Kleinste functioneel onafhankelijk stukje water met gelijkblijvende homogene eigenschappen en relaties dat er binnen een water wordt onderscheiden.

_Inwinningscriteria:_

Maximum breedte voor lijnvormige waterdelen: 6 meter.

Minimum oppervlakte voor vlakvormige waterdelen: 50 m².

Een vlakvormig waterdeel (zee of meer, plas, ven, vijver) kan opgesplitst worden in meerdere delen, zodat het aantal punten niet te groot wordt.

### Attribuut geometriePunt

| Attribuut | geometriePunt |
|:---|:---|
| Definitie | De puntgeometrie van een waterdeel object. |
						 
					
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Point |
| Domein | "Ruimtelijke coördinaten" |
									

### Attribuut geometrieLijn

| Attribuut | geometrieLijn |
|:---|:---|
| Definitie | De lijngeometrie van een waterdeel object. |
			
			
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Curve |
| Domein | "Ruimtelijke coördinaten" |
								 

### Attribuut geometrieVlak

| Attribuut | geometrieVlak |
|:---|:---|
| Definitie | De vlakgeometrie van een waterdeel object. |
			
							
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Surface |
| Domein | "Ruimtelijke coördinaten" |
						 

### Attribuut breedteklasse

| Attribuut | breedteklasse |
|:---|:---|
| Definitie | De breedte van het water ingedeeld in klassen. |
| Inwinningscriteria | De breedte van een natte sloot (een sloot waar het grootste gedeelte van het jaar water in staat) wordt gemeten over de gemiddelde waterbreedte.<br>Waterlopen worden opgenomen indien ze minimaal 50 cm diep en breed zijn. |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Getal |
| Domein | "WA\_breedteklasse"

#### Domein "WA\_breedteklasse"

| Domein | WA\_breedteklasse |
|:---|:---|
| Domeinwaarde | **0,5 - 3 meter** |
| Definitie | De breedte van het water is groter dan of gelijk aan 0,5 meter en minder dan 3 meter. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
							


| Domein | WA\_breedteklasse |
|:---|:---|
| Domeinwaarde | **3 - 6 meter** |
| Definitie | De breedte van het water is groter dan of gelijk aan 3 meter en minder dan 6 meter. |
																																																																																																						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
			

| Domein | WA\_breedteklasse |
|:---|:---|
| Domeinwaarde | **6 - 12 meter** |
| Definitie | De breedte van het water is groter dan of gelijk aan 6 meter en minder dan 12 meter. |
		 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |
			

| Domein | WA\_breedteklasse |
|:---|:---|
| Domeinwaarde | **12 - 50 meter** |
| Definitie | De breedte van het water is groter dan of gelijk aan 12 meter en minder dan 50 meter. |

| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |
						 

| Domein | WA\_breedteklasse |
|:---|:---|
| Domeinwaarde | **50 - 125 meter** |
| Definitie | De breedte van het water is groter dan of gelijk aan 50 meter en minder dan 125 meter. |

| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |
						 

| Domein | WA\_breedteklasse |
|:---|:---|
| Domeinwaarde | **> 125 meter** |
| Definitie | De breedte van het water is groter dan of gelijk aan 125 meter. |

| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |
												 

								
### Attribuut functie
								 
																																		 
						 

| Attribuut | functie |
|:---|:---|
			
| Definitie | De functie van het water. |
							
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "WA\_functie" |
							


#### Domein "WA\_functie"

| Domein | WA\_functie |
|:---|:---|
| Domeinwaarde | **drinkwaterbekken** |
| Definitie | Bassin t.b.v. de drinkwatervoorziening. |
| Inwinningscriteria | Ook een spaarbekken (niet noodzakelijk bedoeld voor de drinkwatervoorziening) wordt als drinkwaterbekken ingewonnen. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |

| Domein | WA\_functie |
|:---|:---|
| Domeinwaarde | **haven** |
| Definitie | Lig- en bergplaats voor vaartuigen. |
| Inwinningscriteria | Tot welk type water een haven behoort, is afhankelijk van het waterdeel waar de haven aan ligt. Is dat waterdeel een "waterloop" dan is ook de haven een "waterloop", is dat waterdeel van de categorie "meer, plas, ven, vijver" dan is de haven ook een "meer, plas, ven, vijver". |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |

| Domein | WA\_functie |
|:---|:---|
| Domeinwaarde | **natuurbad** |
| Definitie | Plas in de natuur, ingericht voor zwemmen en zonnebaden. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |
			

| Domein | WA\_functie |
|:---|:---|
| Domeinwaarde | **viskwekerij** |
| Definitie | Bassin, aangelegd voor het kweken van vis. |
		 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |
					

| Domein | WA\_functie |
|:---|:---|
| Domeinwaarde | **vistrap** |
| Definitie | Omleiding bij een stuw of een deel van een waterloop zodanig ingericht dat vissen stroomopwaarts kunnen passeren. |
| Inwinningscriteria | De in de vistrap gelegen stuwtjes worden niet apart aangegeven. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

| Domein | WA\_functie |
|:---|:---|
| Domeinwaarde | **vloeiveld** |
| Definitie | Omdijkt stuk land, bestemd voor de bezinking van afvalwater. |
			
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |
							 

| Domein | WA\_functie |
|:---|:---|
| Domeinwaarde | **waterval** |
| Definitie | Plaats waar stromend water van een hoogte of helling naar beneden valt. |
			
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
		 

| Domein | WA\_functie |
|:---|:---|
| Domeinwaarde | **waterzuivering** |
| Definitie | Zuivering van afvalwater. |
| Inwinningscriteria | Een bezinkbak (omdijkt of ommuurd vlak, bestemd voor de bezinking van afvalslib) en beluchtingsbak worden, indien deel uitmakend van een zuiveringsinstallatie, ook opgenomen. |
			
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |
									

| Domein | WA\_functie |
|:---|:---|
| Domeinwaarde | **zwembad** |
| Definitie | De waterbak bij een zwembad. |
| Inwinningscriteria | Een zwembassin wordt, indien groter dan 50 m² en openbaar toegankelijk, aangegeven als een waterdeel van het type meer/plas/ven/vijver, met de functie zwembad. |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |

| Domein | WA\_functie |
|:---|:---|
| Domeinwaarde | **overig** |
| Definitie | De waarde van het objectkenmerk is bekend, maar anders dan de genoemde waarden. |
								 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut fysiek voorkomen

| Attribuut | fysiek voorkomen |
|:---|:---|
| Definitie | De plaats waar het object zich bevindt t.o.v. andere constructies. |
			
							
| Inwinningscriteria | - |
| Multipliciteit | Veelvoudig |
			
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Domein | "WA\_fysiekVoorkomen" |
									

										 
				 
						 
#### Domein "WA\_fysiekVoorkomen"
						 
					
			

| Domein | WA\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **in sluis** |
| Definitie | Gelegen in het deel tussen de sluisdeuren van een schutsluis/scheepvaartsluis (de schutkolk/sluiskolk). |
| Inwinningscriteria | Indien een sluisdeur is gelegen onder een wegdeel >2 m op brug wordt deze niet aangegeven. Ook de kolk loopt in dat geval tot de brug. |
									
					
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |
																		 

| Domein | WA\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **op brug** |
| Definitie | Gelegen op een kunstwerk waarmee water over een weg of een ander water wordt gevoerd, zodanig geconstrueerd dat het dak van de onderdoorgang tevens de bodem van het bovengelegen water vormt (aquaduct). |
			
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |
		 

| Domein | WA\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **in duiker** |
| Definitie | Gelegen in een niet afsluitbare koker die dient voor de instandhouding van de verbinding tussen wederzijds gelegen wateren of voor de afwatering van aangrenzende landerijen, niet zijnde een grondduiker. |
| Inwinningscriteria | Elke duiker in het hoofdafwateringspatroon wordt aangegeven en elke duiker onder een dijk of (spoor)weg met een minimale diameter van 60 centimeter. Een duiker in open terrein, niet gelegen in het hoofdafwateringspatroon, wordt aangegeven als (koe)dam. (Koe)dammen gelegen in waterlopen smaller dan 6 meter die onderdeel uitmaken van het hoofdafwateringspatroon worden opgenomen als duiker.<br>Een buis voor het lozen van industrieel water op oppervlaktewater wordt niet opgenomen. |
			
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |
							


| Domein | WA\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **in afsluitbare duiker** |
| Definitie | Gelegen in een afsluitbare koker die dient voor de instandhouding van de verbinding tussen wederzijds gelegen wateren of voor de afwatering van aangrenzende landerijen, niet zijnde een grondduiker. |
| Inwinningscriteria | Elke afsluitbare duiker in het hoofdafwateringspatroon wordt aangegeven en elke afsluitbare duiker onder een dijk of (spoor)weg met een minimale diameter van 60 centimeter. Een afsluitbare duiker in open terrein, niet gelegen in het hoofdafwateringspatroon, wordt aangegeven als (koe)dam. (Koe)dammen gelegen in waterlopen smaller dan 6 meter die onderdeel uitmaken van het hoofdafwateringspatroon worden opgenomen als duiker. Ook een uitwateringssluis (sluis waarmee overtollig water gespuid wordt) wordt opgenomen als waterdeel in afsluitbare duiker, tenzij er een aantal uitwateringssluizen als complex naast elkaar voorkomen. Dan wordt het geheel als functioneel gebied van het type sluizencomplex opgenomen.<br>Een duiker gelegen onder een gemaal of onder een molen van het type windmolen: watermolen wordt altijd gegeven als afsluitbare duiker.<br>Een buis voor het lozen van industrieel water op oppervlaktewater wordt niet opgenomen. |
						 
					
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |
			

| Domein | WA\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **in grondduiker** |
| Definitie | Gelegen in een onder een ander water doorlopende koker, die dient voor de instandhouding van de verbinding tussen wederzijds gelegen wateren of voor de afwatering van aangrenzende landerijen. |
| Inwinningscriteria | Elke grondduiker gelegen in het hoofdafwateringspatroon wordt aangegeven.<br>Een buis voor het lozen van industrieel water op oppervlaktewater wordt niet opgenomen. |
										
					
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |
			

| Domein | WA\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **in afsluitbare grondduiker** |
| Definitie | Gelegen in een onder een ander water doorlopende afsluitbare koker, die dient voor de instandhouding van de verbinding tussen wederzijds gelegen wateren of voor de afwatering van aangrenzende landerijen. |
| Inwinningscriteria | Elke afsluitbare grondduiker in het hoofdafwateringspatroon wordt aangegeven.<br>Een buis voor het lozen van industrieel water op oppervlaktewater wordt niet opgenomen. |
						 
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WA\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **overkluisd** |
| Definitie | Water overbouwd door gebouwen. |
			
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							
### Attribuut getijdeInvloed
																															 
						 
						 

| Attribuut | getijdeInvloed |
|:---|:---|
| Definitie | Aanduiding of het water getijdeinvloed heeft. |
							

| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
			
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "WA\_hoofdafwatering" |
																											

#### Domein "WA\_getijdeInvloed"
				 
						 
						

| Domein | **WA\_getijdeInvloed** |
|:---|:---|
| Domeinwaarde | **ja** |
| Definitie | Het water heeft getijdeinvloed. |

| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
																						 

| Domein | **WA\_getijdeInvloed** |
|:---|:---|
| Domeinwaarde | **nee** |
| Definitie | Het water heeft geen getijdeinvloed. |
			
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut hoofdafwatering
					
			
			

| Attribuut | hoofdafwatering |
|:---|:---|
| Definitie | Aanduiding of het water deel uitmaakt van het hoofdafwateringspatroon (het stelsel van waterlopen in gebruik als primaire afvoermogelijkheid van overtollig oppervlaktewater c.q. aanvoermogelijkheid bij een tekort aan oppervlaktewater, plus bijbehorende kunstwerken). |
									

| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
			
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "WA\_hoofdafwatering" |
						 

#### Domein "WA\_hoofdafwatering"

| Domein | WA\_hoofdafwatering |
|:---|:---|
| Domeinwaarde | **ja** |
| Definitie | Het water maakt deel uit van het hoofdafwateringspatroon. |
									
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
						 

| Domein | WA\_hoofdafwatering |
|:---|:---|
| Domeinwaarde | **nee** |
| Definitie | Het water maakt geen deel uit van het hoofdafwateringspatroon. |
							
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut type water
			
			
			

| Attribuut | type water |
|:---|:---|
| Definitie | Het type water. |
		 
		 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "WA\_typeWater" |
			

#### Domein "WA\_typeWater"

| Domein | WA\_typeWater |
|:---|:---|
| Domeinwaarde | **waterloop** |
| Definitie | Langgerekt waterdeel in de vorm van een sloot, rivier, kanaal, enz.. |
| Inwinningscriteria | Als waterloop worden beschouwd:<br>- Beek (natuurlijke waterloop, ontstaan uit een bron).<br>- Boezem (het geheel aan stilstaande, gemeen liggende, doch van het buitenwater afgesloten plassen, kanalen, tochten en sloten, waarop het overtollige water uit lager gelegen polders wordt uitgeslagen. Karakteristiek hierbij is dat het waterniveau hoger is dan het naastliggende maaiveldniveau).<br>- Gracht (gegraven geul).<br>- Kanaal (een ten behoeve van de waterbeheersing of scheepvaart gegraven geul).<br>- Kreek (klein, smal, niet gegraven water, dikwijls een inham van een zee, ook wel een overblijfsel van een overstroming). Worden gegeneraliseerd aangegeven.<br>- Natte sloot (sloot waar het grootste gedeelte van het jaar water in staat).<br>- Rivier (natuurlijke waterloop).<br>- Sprang / Sprank / Spreng (sloot of kanaal in zandgrond tot verzameling van het in de bodem aanwezige water t.b.v. de drinkwatervoorziening).<br>- Vaart (kanaal, gegraven waterweg).<br>- Vistrap (omleiding bij een stuw of een deel van een waterloop zodanig ingericht dat vissen stroomopwaarts kunnen passeren).<br>- Wijk (sloot of kanaal in veenkoloniaal gebied). |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |

| Domein | WA\_typeWater |
|:---|:---|
| Domeinwaarde | **meer, plas** |
| Definitie | Water (meestal) niet gelegen in een waterloop. |
| Inwinningscriteria | Als meer, plas worden beschouwd:<br>- Bezinkbak (omdijkt of ommuurd vlak, bestemd voor de bezinking van afvalslib).<br>- Brandput (verdieping in het terrein, gevuld met water, waar bij brand bluswater gehaald kan worden).<br>- Drinkplaats (verdieping in het terrein, gevuld met water, bestemd om vee te drenken).<br>- Drinkwaterbekken (bassin t.b.v. de drinkwatervoorziening).<br>- Kolk (waterput van extreme diepte in vergelijking met de oppervlakte).<br>- Meer (grote watervlakte, ontstaan op natuurlijke wijze, dan wel door menselijk ingrijpen).<br>- Natuurbad (plas in de natuur, ingericht voor zwemmen en zonnebaden).<br>- Plas (watervlakte, ontstaan op natuurlijke wijze, dan wel door menselijk ingrijpen).<br>- Poel (klein, ondiep, stilstaand water).<br>- Spaarbekken (bekken waarin water wordt verzameld om op andere tijden te worden gebruikt o.a. als drinkwater).<br>- Ven (klein, ondiep, stilstaand water in bos- of heidegebied, dat in tijden van grote droogte leeg kan staan en betreedbaar kan zijn).<br>- Vijver (aangelegde waterkom in een tuin, park, plantsoen e.d.).<br>- Viskwekerij (bassin, aangelegd voor het kweken van vis).<br>- Visvijver (plas met voorzieningen t.b.v. het sportvissen).<br>- Vloeiveld (omdijkt stuk land, bestemd voor bezinking van afvalwater).<br>- Wiel (plas ontstaan als gevolg van uitspoeling na een dijkdoorbraak).<br>- Zwembassin (waterbak bij een zwembad).<br>Omdat een ven ondiep is, kan de oeverlijn sterk fluctueren, maar de oorspronkelijke vastlegging hiervan wordt echter zoveel mogelijk gehandhaafd.<br>Een niet-ronde waterbak groter dan 50 m² wordt ook opgenomen (indien de waterbak rond is, dan wordt deze als gebouw van het type tank opgenomen).<br>Opnamecriterium: minimumgrootte 50 m². |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | WA\_typeWater |
|:---|:---|
| Domeinwaarde | **greppel, droge sloot** |
| Definitie | Een in het algemeen niet watervoerende sloot. |
| Inwinningscriteria | Een greppel wordt gegeven indien hij minimaal 50 cm diep en breed is. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | WA\_typeWater |
|:---|:---|
| Domeinwaarde | **zee** |
| Definitie | Uitgestrekt oppervlak zout water dat het grootste deel van de aarde bedekt. |
| Inwinningscriteria | Het waterdeel in een haven aan zee heeft ook de attribuutwaarde zee.<br>De overgang naar waterloop of meer, .plas, ven, vijver ligt op een sluis (bv. haven Den Helder en IJmuiden, Haringvlietsluizen). Nieuwe Waterweg: compleet waterloop en dus geen zee. De overgang naar de Noordzee ligt aan het eind van de Noorderdam, haaks over de Nieuwe Waterweg (tussen de twee landhoofden). Oosterschelde: compleet zee, tot de Philipsdam en de Oesterdam. Westerschelde: compleet zee, de overgang naar waterloop ligt bij de Stroomleidam (ter hoogte van de rijksgrens met België). De overgang ligt op de dam en vanaf het einde van de dam haaks over de Schelde. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | WA\_typeWater |
|:---|:---|
| Domeinwaarde | **droogvallend** |
| Definitie | Geheel of gedeeltelijk droogvallende gronden, buitendijks gelegen, begrensd door de hoogwaterlijn op gemiddeld hoog water en de laagwaterlijn op gemiddeld laag water. |
| Inwinningscriteria | Het terrein, gelegen tussen de hoogwaterlijn en de waterkering (dijk), wordt aangegeven volgens de aanwezige vegetatie. Het gedeelte tussen de hoogwaterlijn en de laagwaterlijn wordt aangegeven als een waterdeel van het type 'droogvallend'. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | WA\_typeWater |
|:---|:---|
| Domeinwaarde | **droogvallend (LAT)** |
| Definitie | Geheel of gedeeltelijk droogvallende gronden, buitendijks gelegen, begrensd door de laagwaterlijnen op gemiddeld laag water en op laagste astronomisch getij (LAT). |
| Inwinningscriteria | Ingewonnen op basis van gegevens van de Dienst der Hydrografie. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | WA\_typeWater |
|:---|:---|
| Domeinwaarde | **bron, wel** |
| Definitie | Plaats waar op natuurlijke wijze water uit de grond opwelt. |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Nee |
									 

| Domein | WA\_typeWater |
|:---|:---|
| Domeinwaarde | **overig** |
| Definitie | De waarde van het objectkenmerk is bekend, maar anders dan de genoemde waarden. |
			
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |
								

			


### Attribuut vaarwegklasse

| Attribuut | vaarwegklasse |
|:---|:---|
| Definitie | CEMT klasses van vaarwegen, welke gebaseerd zijn op de afmetingen en laadvermogen van standaardschepen en duwstellen voor de binnen- en riviervaart in West-Europa. De klasses I t/m VII zijn in 1992 bepaald door de Conferentie van Europese Ministers van Verkeer (C.E.M.T.). Naderhand is klasse 0 (vaarwegen kleiner dan die van klasse I) daaraan toegevoegd. Klasse VII komt in Nederland niet voor. |
							

| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Domein | "WA\_vaarwegklasse" |
						 

#### Domein "WA\_vaarwegklasse"
			
			
							

| Domein | **WA\_vaarwegklasse** |
|:---|:---|
| Domeinwaarde | **0** |
| Definitie | Vaarweg geschikt voor kleinere vaartuigen en recreatievaart (laadvermogen < 250 ton). |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | **WA\_vaarwegklasse** |
|:---|:---|
| Domeinwaarde | **I** |
| Definitie | Vaarweg geschikt voor Spits (laadvermogen 250 - 400 ton). |
									 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
			

| Domein | **WA\_vaarwegklasse** |
|:---|:---|
| Domeinwaarde | **II** |
| Definitie | Vaarweg geschikt voor Kempenaar (laadvermogen 400 - 650 ton). |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |

| Domein | **WA\_vaarwegklasse** |
|:---|:---|
| Domeinwaarde | **III** |
| Definitie | Vaarweg geschikt voor Dortmund-Eemskanaalschip (laadvermogen 650 - 1000 ton). |
							
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
						 

| Domein | **WA\_vaarwegklasse** |
|:---|:---|
| Domeinwaarde | **IV** |
| Definitie | Vaarweg geschikt voor Rijn-Hernekanaalschip (laadvermogen 1000 - 1500 ton) en voor 1-baksduwstel (laadvermogen 1250-1450 ton). |
							
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
								 

| Domein | **WA\_vaarwegklasse** |
|:---|:---|
| Domeinwaarde | **Va** |
| Definitie | Vaarweg geschikt voor Groot Rijnschip (laadvermogen 1500 - 3000 ton) en voor 1-baksduwstel (laadvermogen 1600-3000 ton). |
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

| Domein | WA\_vaarwegklasse |
|:---|:---|
| Domeinwaarde | **Vb** |
| Definitie | Vaarweg geschikt voor 2-baksduwstel - achter elkaar (laadvermogen 3200 - 6000 ton). |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | **WA\_vaarwegklasse** |
|:---|:---|
| Domeinwaarde | **VIa** |
| Definitie | Vaarweg geschikt voor 2-baksduwstel - naast elkaar (laadvermogen 3200 - 6000 ton). |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | **WA\_vaarwegklasse** |
|:---|:---|
| Domeinwaarde | **VIb** |
| Definitie | Vaarweg geschikt voor 4-baksduwstel - 2 naast elkaar, 2 achter elkaar (laadvermogen 6000 - 12000 ton). |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | **WA\_vaarwegklasse** |
|:---|:---|
| Domeinwaarde | **VIc** |
| Definitie | Vaarweg geschikt voor 6-baksduwstel - 2 naast elkaar, 3 achter elkaar of 3 naast elkaar, 2 achter elkaar (laadvermogen 9600 - 18000 ton). |
									 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
			

| Domein | WA\_vaarwegklasse |
|:---|:---|
| Domeinwaarde | **VII** |
| Definitie | Vaarweg geschikt voor 9-baksduwstel - 3 naast elkaar, 3 achter elkaar (laadvermogen 14500 - 27000 ton). |
		 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
					

### Attribuut voorkomen

| Attribuut | voorkomen |
|:---|:---|
| Definitie | Aanduiding dat er riet op het waterdeel voorkomt. |
													 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Domein | "WA\_voorkomen" |
							

#### Domein "WA\_voorkomen"

| Domein | WA\_voorkomen |
|:---|:---|
| Domeinwaarde | **met riet** |
| Definitie | Een met riet bedekt oppervlak. |
| Inwinningscriteria | Minimum oppervlakte: 1000 m².<br>Rietkragen smaller dan 6 meter worden niet gegeven. |
			
| Volledigheid | Beperkt |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |
									

### Attribuut naam (Nl)
			
							


| Attribuut | naam (Nl) |
|:---|:---|
| Definitie | De Nederlandse naam van het water. |
| Inwinningscriteria | Indien het waterdeel de functie 'haven' heeft, dan mag de soortnaam 'vluchthaven' of 'werkhaven' worden opgenomen. |
| Volledigheid | Beperkt |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut naam (Fr)

| Attribuut | naam (Fr) |
|:---|:---|
| Definitie | De Friese naam van het water. |
| Inwinningscriteria | Wordt alleen in Friesland ingewonnen. |
| Volledigheid | Beperkt |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut naam Officieel

| Attribuut | naam Officieel |
|:---|:---|
| Definitie | De officiële naam van het water. |
| Inwinningscriteria | Indien het waterdeel de functie 'haven' heeft, dan mag de soortnaam 'vluchthaven' of 'werkhaven' worden opgenomen. |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut isBAGnaam

| Attribuut | isBAGnaam |
|:---|:---|
| Definitie | Aanduiding of de naam geverifieerd is met de BAG. |
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Domein | "WA\_isBAGnaam" |
									

#### Domein "WA\_isBAGnaam"

| Domein | WA\_isBAGnaam |
|:---|:---|
| Domeinwaarde | **ja** |
| Definitie | De naam is geverifieerd met de BAG. |
					
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
									

| Domein | WA\_isBAGnaam |
|:---|:---|
| Domeinwaarde | **nee** |
| Definitie | De naam is geverifieerd met de BAG. |
					
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
									

### Attribuut sluisnaam
		 
							 
									

| Attribuut | sluisnaam |
|:---|:---|
			
| Definitie | De naam van de sluis. |
			
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut brugnaam

| Attribuut | brugnaam |
|:---|:---|
					
| Definitie | De naam van een brug. |
			
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut hoogteniveau

| Attribuut | hoogteniveau |
|:---|:---|
						 
| Definitie | Het hoogteniveau van het object. |
			
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Geheel getal |
| Domein | ≤ 0 (0, -1, -2, -3, …) |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

## 7.2 Objectklasse: wegdeel
								 

_Definitie:_

Kleinste functioneel onafhankelijk stukje weg met gelijkblijvende, homogene eigenschappen en relaties voor wegverkeer en vliegverkeer te land. Hieronder wordt het gehele weglichaam begrepen (incl. rijstroken, trottoirs, bermen, etc.).

_Inwinningscriteria:_

Een weg smaller dan 2 meter wordt aangegeven als een lijnobject samenvallend met het midden van de weg. Een weg breder dan 2 meter wordt aangegeven als een vlakobject, waarvan de contouren worden aangegeven, samenvallend met de kant van de verharding van een verharde weg c.q. de berijdbare strook van een onverharde weg.

Een berm smaller dan 6 meter zonder bebouwing, talud of brede houtrand wordt bij het wegdeel getrokken als de berm begrensd wordt door een waterloop, bebouwd oppervlak of een andere weg (uitgezonderd een rijwielpad smaller dan 2 meter). Een berm met talud wordt ongeacht de breedte als terrein met reliëf opgenomen.

Niet-openbare wegen op een circuit, wegen van een kartbaan, tankbanen (niet gelegen in een zandvlakte), wegen op een vliegveld/luchthaven (niet zijnde startbaan, landingsbaan, rolbaan of platform) en wegen op een volkstuincomplex worden opgenomen als wegdeel met als type weg en hoofdverkeersgebruik 'overig'.

Wegen van een crossbaan gelegen in een bos worden altijd opgenomen als wegdeel met als type wegen hoofdverkeersgebruik 'overig' en verhardingstype 'onverhard'. Wegen van een crossbaan buiten een bos worden alleen ingewonnen als de crossbaan meer dan 10.000 m² groot is. Bij andere crossbanen worden de wegen niet opgenomen.

Minimumlengte van op- en afritten van een dijk: 100 meter.

Er wordt geen verbinding gemaakt tussen wegen die op een erf uitkomen, maar openbare wegen die via het erf lopen worden wel opgenomen.

Een weg uitsluitend bestemd voor voetgangers rondom een sportveld wordt niet ingewonnen. Een weg uitsluitend bestemd voor voetgangers als toegangspad of gemeenschappelijk pad rond huizen, huizenrijen, flatgebouwen en dergelijke wordt niet opgenomen.

De wegen op een fruitkwekerij worden gegeneraliseerd weergegeven.

De toe- en uitrit van een tankstation of verzorgingsplaats wordt altijd opgenomen als lokale weg met een breedte van 4 tot 7 meter.

Een trap, hemelsbreed langer dan 100 meter wordt aangegeven als wegdeel met hoofdverkeersgebruik 'voetgangers' en breedteklasse '< 2 meter'. Een trap, hemelsbreed korter dan 100 meter, wordt niet aangegeven, tenzij het onderdeel is van een voetpad smaller dan 2 meter. Een trap gelegen in een voetgangersgebied wordt niet apart aangegeven.

Een steeg (nauwe straat binnen bebouwd gebied, smaller dan 2 meter) wordt als vlak ingewonnen waarbij de aanliggende gebouwen vertekend worden.

Een wisselstrook krijgt dezelfde attribuutwaarden als de rest van de weg.

### Attribuut geometriePunt

| Attribuut | geometriePunt |
|:---|:---|
| Definitie | De puntgeometrie van een wegdeel object. |
																																	
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Point |
| Domein | "Ruimtelijke coördinaten" |
							

### Attribuut geometrieLijn

| Attribuut | geometrieLijn |
|:---|:---|
| Definitie | De lijngeometrie van een wegdeel object. |
									 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Curve |
| Domein | "Ruimtelijke coördinaten" |
							

### Attribuut geometrieVlak

| Attribuut | geometrieVlak |
|:---|:---|
| Definitie | De vlakgeometrie van een wegdeel object. |
																					
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Surface |
| Domein | "Ruimtelijke coördinaten" |
							

### Attribuut hartPunt

| Attribuut | hartPunt |
|:---|:---|
| Definitie | De hartpuntgeometrie van een wegdeel object. |
										
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Point |
| Domein | "Ruimtelijke coördinaten" |
							

### Attribuut hartLijn

| Attribuut | hartLijn |
|:---|:---|
| Definitie | De hartlijngeometrie van een wegdeel object. |
																															
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | GM\_Curve |
| Domein | "Ruimtelijke coördinaten" |
							

### Attribuut fysiek voorkomen

| Attribuut | fysiek voorkomen |
|:---|:---|
| Definitie | De plaats waar het object zich bevindt t.o.v. andere constructies. |
																							
						 
| Inwinningscriteria | - |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Domein | "WE\_fysiekVoorkomen" |
							

#### Domein "WE\_fysiekVoorkomen"

| Domein | WE\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **op vast deel van brug** |
| Definitie | Gelegen op een niet beweegbaar deel van een kunstwerk dat een verbinding vormt door middel van een overspanning. |
| Inwinningscriteria | Iedere brug wordt ingewonnen tenzij het een brug betreft die direct vanaf een weg toegang geeft tot bebouwing, een landerij etc. én geen relatie heeft met een weg.<br>Uitzondering: Losse voetgangersbruggen, niet gelegen in een pad of rijwielpad, worden aangegeven als een voetpad met de attribuutwaarde op vast deel van brug. Deze bruggen zijn interessant voor bv. wandelaars. Indien er over een waterloop veel losse voetgangersbruggen naast elkaar voorkomen, worden deze gegeneraliseerd weergegeven. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **op beweegbaar deel van brug** |
| Definitie | Gelegen op een beweegbaar deel van een kunstwerk dat een verbinding vormt door middel van een overspanning. |
| Inwinningscriteria | Iedere beweegbare brug wordt ingewonnen tenzij het een brug betreft die direct vanaf een weg toegang geeft tot bebouwing, een landerij etc. én geen relatie heeft met een weg.<br>Uitzondering: Losse voetgangersbruggen, niet gelegen in een pad of rijwielpad, worden aangegeven als een voetpad met de attribuutwaarde op beweegbaar deel van brug. Deze bruggen zijn interessant voor bv. wandelaars. Indien er over een waterloop veel losse voetgangersbruggen naast elkaar voorkomen, worden deze gegeneraliseerd weergegeven. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

| Domein | WE\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **op rotonde** |
| Definitie | Deel van weg onderdeel zijnde van een rotonde. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **op oprit / afrit** |
| Definitie | Deel van weg onderdeel zijnde van een op- of afrit van een autosnelweg of hoofdweg. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **op knooppuntverbinding** |
| Definitie | Deel van een weg gelegen op een verkeersknooppunt van snelwegen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **overkluisd** |
| Definitie | Overbouwd door gebouwen, zodanig dat de orthogonale projectie van de gebouwen op of over het object valt. |
| Inwinningscriteria | Wordt aangegeven voor de objectklassen Wegdeel, Spoorbaandeel, Waterdeel en Terrein.<br>Een overkluizing wordt niet aangeven in het geval van kleine oversteekjes. Bij de objectklasse terrein is de minimale maat 100 m2, de andere objectklassen kennen geen minimummaat.<br>Het verloop van het object onder de bebouwing, wordt volgens de meest waarschijnlijke vorm aangegeven. Een overkluizing is geen aanleiding tot verandering van het hoogteniveau..<br>Wanneer een weg voor een gedeelte van de breedte overkluisd is, wordt het gehele wegdeel waarvoor dit geldt overkluisd (i.v.m. hartlijn). |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

| Domein | WE\_fysiekVoorkomen |
|:---|:---|
| Domeinwaarde | **in tunnel** |
| Definitie | Gelegen in een kunstmatig aangelegde, onderaardse of door een berg geboorde kokervormige doorgang. |
| Inwinningscriteria | Voor vastlegging van het verloop van een tunnel is een overzichtskaart noodzakelijk.<br>Een veetunnel smaller dan 2 m wordt gegeven door het aanbrengen van een voetpad<2m in tunnel, ongeacht de lengte.<br>Een op zichzelf staande veetunnel breder dan 2 m wordt gegeven door het aanbrengen van een vlak overig in tunnel.<br>Een voetgangerstunnel smaller dan 2 m wordt gegeven door het aanbrengen van een voetpad<2m in tunnel, ongeacht de lengte.<br>Een voetgangerstunnel breder dan 2 m wordt gegeven door het aanbrengen van een wegvlak van het type voetpad>2 m in tunnel ongeacht de lengte. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut hoofdverkeersgebruik
				 
					 
						 

| Attribuut | hoofdverkeersgebruik |
|:---|:---|
| Definitie | Soort verkeer waarvoor een weg bestemd is. |
									 
						 
| Inwinningscriteria | - |
| Multipliciteit | Veelvoudig (type infrastructuur = "kruising") / Enkelvoudig (type infrastructuur = "verbinding" of type infrastructuur = "overig verkeersgebied") |
			
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "WE\_hoofdverkeersgebruik" |
							

#### Domein "WE\_hoofdverkeersgebruik"
				 
						
								 

| Domein | WE\_hoofdverkeersgebruik |
|:---|:---|
| Domeinwaarde | **snelverkeer** |
| Definitie | Weg, bestemd voor motorvoertuigen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_hoofdverkeersgebruik |
|:---|:---|
| Domeinwaarde | **gemengd verkeer** |
| Definitie | Weg, bestemd voor allerlei soorten verkeer. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_hoofdverkeersgebruik |
|:---|:---|
| Domeinwaarde | **busverkeer** |
| Definitie | Weg speciaal bestemd voor openbaar vervoer. |
| Inwinningscriteria | Indien een busbaan is geïntegreerd in een bredere weg (dus als er op de grens tussen de busbaan en de rest van de weg geen fysieke barrière is om oneigenlijk gebruik te verhinderen), dan wordt de busbaan niet apart aangegeven. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_hoofdverkeersgebruik |
|:---|:---|
| Domeinwaarde | **fietsers, bromfietsers** |
| Definitie | Weg uitsluitend bestemd voor fietsers en/of bromfietsers en daartoe aangeduid met een blauw bord met daarop een wit rijwiel, of een blauw of zwart bord met daarop de tekst "FIETSPAD" of "RIJWIELPAD". Indien, in uitzonderlijke gevallen, met grote mate van zekerheid bepaald kan worden dat een weg/pad een rijwielpad is, mag afgeweken worden van de regel dat er een aanduiding moet zijn. |
| Inwinningscriteria | Een vrijliggend rijwielpad (waar niet direct een ander wegdeel naast ligt) breder dan 2 meter wordt altijd aangegeven.<br>Een parallel gelegen rijwielpad (direct gelegen naast een ander wegdeel, met een fysieke scheiding ertussen) breder dan 2 meter, buiten bebouwd gebied, wordt altijd aangegeven.<br>Een parallel gelegen rijwielpad breder dan 2 meter, binnen bebouwd gebied, wordt alleen gegeven naast een autosnelweg, hoofdweg, regionale weg of lokale weg.<br>Een vrijliggend rijwielpad smaller dan 2 meter, wordt altijd aangegeven.<br>Een parallel gelegen rijwielpad smaller dan 2 meter buiten bebouwd gebied wordt aangegeven op de rand van het naastliggende wegvlak.<br>Een parallel gelegen rijwielpad smaller dan 2 meter binnen bebouwd gebied wordt niet aangegeven.<br>Een vrijliggend rijwielpad binnen bebouwd gebied dat over een relatief korte afstand parallel ligt langs een niet geclassificeerde weg, wordt wel aangegeven.<br>Rijwielpaden toegankelijk voor bestemmingsverkeer krijgen als hoofdverkeersgebruik 'fietsers, bromfietsers'.<br>Een rijwielpad geïntegreerd in een voetgangersgebied wordt niet apart aangegeven.<br>Een fietsstraat wordt ingewonnen als straat. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

| Domein | WE\_hoofdverkeersgebruik |
|:---|:---|
| Domeinwaarde | **voetgangers** |
| Definitie | Weg, uitsluitend bestemd voor voetgangers. |
| Inwinningscriteria | Voetpaden smaller dan 2 meter worden alleen ingewonnen indien vrijliggend van andere wegdelen en langer dan 100 meter.<br>In uitzonderingssituaties mag, in geval van een duidelijke verbinding (als afkorting van een veel langer wegdeel van het type gemengd verkeer), een pad korter dan 100 m wel gegeven worden.<br>Een koepad <2 m, gelegen achter een boerderij, wordt gegeven als voetpad indien hij langer is dan 250 m.<br>Een voetpad toegankelijk voor bestemmingsverkeer krijgt alleen 'voetgangers' als hoofdverkeersgebruik. Een voetpad als toegangspad of gemeenschappelijk pad rond huizen, huizenrijen, flatgebouwen e.d. v wordt niet aangegeven. Een voetpad dat onderdeel is van een doorlopend geheel en over een relatief korte afstand parallel ligt langs een niet geclassificeerde weg, wordt wel aangegeven. Belangrijke voetpaden (belangrijk voor de wijk waarin ze voorkomen) mogen gegeven worden, ook als ze korter zijn dan 100 m, mits ze onderdeel zijn van een logisch doorlopend geheel met een minimum lengte van 250 meter.<br>Losse voetgangersbruggen, niet gelegen in een pad of rijwielpad, worden aangegeven als een voetpad met de attribuutwaarde op vast deel van brug / op beweegbaar deel van brug. Deze bruggen zijn interessant voor bv. wandelaars. Indien er over een waterloop veel losse voetgangersbruggen naast elkaar voorkomen, worden deze gegeneraliseerd weergegeven. |
						 
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_hoofdverkeersgebruik |
|:---|:---|
| Domeinwaarde | **ruiters** |
| Definitie | Weg bestemd voor paardrijders. |
| Inwinningscriteria | -<br>Wordt niet ingewonnen. |
						 
| Volledigheid | Niet |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_hoofdverkeersgebruik |
|:---|:---|
| Domeinwaarde | **vliegverkeer** |
| Definitie | Weg, bestemd voor luchtvaartuigen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_hoofdverkeersgebruik |
|:---|:---|
| Domeinwaarde | **overig** |
| Definitie | De waarde van het objectkenmerk is bekend, maar anders dan de genoemde waarden. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							
### Attribuut type infrastructuur

| Attribuut | type infrastructuur |
|:---|:---|
| Definitie | Aanduiding of het object een verbinding, een kruising of een overig verkeersgebied is. |
										 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "WE\_typeInfrastructuur" |
							

#### Domein "WE\_typeInfrastructuur"

| Domein | WE\_typeInfrastructuur |
|:---|:---|
| Domeinwaarde | **verbinding** |
| Definitie | Wegdeel waar maximaal twee hartlijnen van andere wegdelen op aansluiten. |
| Inwinningscriteria | Een wegdeel van het type verbinding heeft meestal als hoofdgeometrie een wegvlak of een weglijn. Soms heeft het geen hoofdgeometrie.<br>Een wegdeel van het type verbinding heeft altijd een hartlijn. |
						 
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_typeInfrastructuur |
|:---|:---|
| Domeinwaarde | **kruising** |
| Definitie | Gelijkvloerse kruising (wegdeel waar drie of meer hartlijnen van verbindingen op elkaar aansluiten). |
| Inwinningscriteria | Een wegdeel van het type kruising heeft meestal als hoofdgeometrie een wegvlak of een wegpunt. Soms heeft het geen hoofdgeometrie.<br>Een wegdeel van het type kruising heeft altijd een hartpunt.<br>Het kruisingsvlak wordt geplaatst, daar waar twee wegvlakken elkaar kruisen of zoals bij op – en afritten, daar waar de wegvlakken bij elkaar komen. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | WE\_typeInfrastructuur |
|:---|:---|
| Domeinwaarde | **overig verkeersgebied** |
| Definitie | Een wegdeel anders dan een verbinding of kruising. |
| Inwinningscriteria | Een wegdeel van het type overig verkeersgebied heeft als hoofdgeometrie een wegvlak.<br>Een wegdeel van het type overig verkeersgebied heeft geen hartlijn en geen hartpunt.<br>Overige verkeersgebied wordt alleen gebruikt voor voetgangersgebieden en parkeerplaatsen. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

### Attribuut type weg

| Attribuut | type weg |
|:---|:---|
| Definitie | Het soort weg. |
| Inwinningscriteria | Wegen worden hiërarchisch opgedeeld in een aantal categorieën, welke met dit attribuut worden aangeduid.<br>Een op- of afrit en een rotonde wordt aangegeven als een wegdeel van de hoogst geclassificeerde route (Volgorde van classificatie van hoog naar laag: 1 autosnelweg, 2 hoofdweg, 3 regionale weg, 4 lokale weg, 5 alle andere). Echter, als van een autosnelweg of hoofdweg voor snelverkeer een op/afrit op een rotonde uitkomt, dan vervalt de regel van hoogst geclassificeerde route, en krijgt de rotonde de code van de doorgaande route.<br>Autosnelwegen en hoofdwegen vormen samen een gesloten netwerk. Autosnelwegen, hoofdwegen en regionale wegen vormen ook een gesloten netwerk. |
| Multipliciteit | Veelvoudig (type infrastructuur = "kruising") / Enkelvoudig (type infrastructuur = "verbinding" of type infrastructuur = "overig verkeersgebied") |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "WE\_typeWeg" |

#### Domein "WE\_typeWeg"
| Domein | WE\_typeweg |
|:---|:---|
| Domeinwaarde | **startbaan, landingsbaan** |
| Definitie | Strook grond waar vliegtuigen kunnen opstijgen en/of landen. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_typeweg |
|:---|:---|
| Domeinwaarde | **rolbaan, platform** |
| Definitie | Afgebakende taxibaan op een vliegveld (rolbaan). / Terrein voor geparkeerd staande vliegtuigen (platform). |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							
| Domein | WE\_typeweg |
|:---|:---|
| Domeinwaarde | **autosnelweg** |
| Definitie | Weg met gescheiden rijbanen en ongelijkvloerse kruisingen, daartoe aangeduid met het betreffende verkeersbord. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_typeweg |
|:---|:---|
| Domeinwaarde | **hoofdweg** |
| Definitie | Verharde weg die is aangeduid met een E-nummer, maar niet met een A-nummer, of verharde weg die onderdeel is van een verbindingsroute tussen grotere plaatsen, wat blijkt uit blauwe ANWB-borden, dan wel onderdeel is van een route om eindigende A of E-routes tot een gesloten netwerk te completeren. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_typeweg |
|:---|:---|
| Domeinwaarde | **regionale weg** |
| Definitie | Verharde weg die een verbinding vormt tussen bewoonde oorden of grote stadswijken en daartoe van twee kanten bewegwijzerd zijn met blauwe ANWB-richtingsborden voor autoverkeer. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_typeweg |
|:---|:---|
| Domeinwaarde | **lokale weg** |
| Definitie | Weg van lokaal belang tussen bewegwijzerde routes. |
| Inwinningscriteria | - De belangrijkste straat (straten) binnen een wijk van tenminste 1 km2.<br>- Belangrijke ontsluitingswegen zijn bewegwijzerd met witte ANWB-borden.<br>- Aan- en afvoerwegen naar bebouwingsconcentraties (ook als deze doodlopend zijn) die veel verkeer aantrekken zoals winkel- en wijkcentra, industrieterreinen, stations, ziekenhuizen en aanverwante inrichtingen, kampeerterreinen, kazernes etc…<br>- Een doodlopende weg langer dan 250 meter wordt ingewonnen als 'lokale weg' als deze verhard is of geen toegangsweg is. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

| Domein | WE\_typeweg |
|:---|:---|
| Domeinwaarde | **straat** |
| Definitie | Weg van zeer plaatselijk belang, gelegen binnen bebouwd gebied. |
| Inwinningscriteria | Breder dan 2 meter.<br>Weg gelegen binnen bebouwd gebied, niet behorende tot de categorieën Autosnelweg,<br>Hoofdweg, Regionale weg en Lokale weg, ongeacht de verharding en lengte.<br>Uitzondering: Doodlopende wegen naar of tussen schuurtjes, garageboxen, parkeerterreintjes (< 1000 m2) gelegen achter bebouwing, etc., korter dan 100 meter, worden ongeacht de verharding weggelaten. Wegen langer dan 100 meter worden aangegeven als straat. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |


| Domein | WE\_typeweg |
|:---|:---|
| Domeinwaarde | **veerverbinding** |
| Definitie | Vastgelegde route over water om voertuigen en personen over te zetten al dan niet op basis van een vaste dienstregeling |
| Inwinningscriteria | Een veerverbinding komt in verschillende verschijningsvormen voor:<br>- Veerdienst: veer met een dienstregeling tussen twee plaatsen / havens. Wordt ingewonnen als 'veerverbinding' met hoofdverkeersgebruik 'gemengd verkeer' én bij de attribuutwaarde "naam" de tekst "Veerdienst <plaats1> - <plaats2>".<br>- Pontveer: veer voor het overzetten van voertuigen en personen. Wordt ingewonnen als 'veerverbinding' met hoofdverkeersgebruik 'gemengd verkeer'<br>- Fietsveer: veer voor het overzetten van fietsers / bromfietsers en personen. Wordt ingewonnen als 'veerverbinding' met hoofdverkeersgebruik 'fietsers, bromfietsers'. Ook een losliggend fietsveer worden ingewonnen als fietsveer.<br>- Voetveer: veer voor het overzetten van personen. Wordt ingewonnen als 'veerverbinding' met hoofdverkeersgebruik 'voetgangers'. Ook een losliggend voetveer wordt ingewonnen als voetveer. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Ja |
| Vlak | Nee |

| Domein | WE\_typeweg |
|:---|:---|
| Domeinwaarde | **parkeerplaats** |
| Definitie | Parkeergelegenheid voor meerdere voertuigen in de openlucht. |
| Inwinningscriteria | Parkeerplaatsen worden gegeven als deze openbaar zijn en groter zijn dan 1000m². Parkeerterreinen kleiner dan 1000 m² in een bosrijk natuurgebied én van oriënterende waarde worden ook ingewonnen. |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |

| Domein | WE\_typeweg |
|:---|:---|
| Domeinwaarde | **parkeerplaats: carpool** |
| Definitie | Parkeerplaats voor personenwagens langs doorgaande wegen t.b.v. carpoolers. |
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | WE\_typeweg |
|:---|:---|
| Domeinwaarde | **parkeerplaats: P+R** |
| Definitie | Parkeergelegenheid ten behoeve van het overstappen op het openbaar vervoer. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Nee |
| Lijn | Nee |
| Vlak | Ja |
							

| Domein | WE\_typeweg |
|:---|:---|
| Domeinwaarde | **overig** |
| Definitie | De waarde van het objectkenmerk is bekend, maar anders dan de genoemde waarden. |
| Inwinningscriteria | Niet-openbare wegen op een circuit en wegen van een crossbaan gelegen in een bos worden als overige weg ingewonnen. Wegen op een vliegveld/luchthaven die geen start- of landingsbaan, rolbaan of platform zijn worden altijd als overige weg ingewonnen.<br>Doodlopende wegen en toegangswegen langer dan 100 meter en korter dan 250 meter worden ingewonnen als 'overige weg'.<br>Een toegangsweg langer dan 250 meter met wegafsluiter (open of dicht) naar landerij(en) worden gegeven als 'overige weg'.<br>Wegen achter bebouwing, doodlopend in het terrein, met een minimum lengte van 250 meter worden ingewonnen als 'overige weg'. |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
			
							


							

### Attribuut verhardingsbreedteklasse

| Attribuut | verhardingsbreedteklasse |
|:---|:---|
| Definitie | De breedte van de verharding, ingedeeld in klassen. |
| Inwinningscriteria | Bij het bepalen van de wegbreedte wordt tot de verharding gerekend: het verharde rijgedeelte, beton- en klinkerrand op gelijk niveau als het wegdek, berijdbare goot en in de rijbaan geïntegreerde rijwielstrook, weg/ busbaan en parkeerstrook (aangegeven door b.v. een witte streep). Niet meegerekend worden: opstaande randen, parkeerhavens, groenstenen en bermverharding in de vorm van sintels, puin e.d.. Duidelijk zichtbare, plaatselijke versmallingen of verbredingen worden alleen opgemeten als deze zich over een afstand van tenminste 500 meter voortzetten (dus geen bruggen e.d.). Vluchtheuvels en verkeersgeleiders in de vorm van opstaande randen worden, mits ze korter zijn dan 500 meter, bij de bepaling van de wegbreedte buiten beschouwing gelaten.<br>Wegen van het type "straat" worden ingewonnen met verhardingsbreedteklasse = "2 – 4 meter" ongeacht de werkelijke verhardingsbreedte.<br>Wegen van het type "overig" en breder dan 2 meter, worden ingewonnen met verhardingsbreedteklasse = "2 – 4 meter" ongeacht de werkelijke verhardingsbreedte. Dit geldt bijvoorbeeld voor toegangswegen, busbanen, half-verharde wegen of onverharde wegen. |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Domein | "WE\_verhardingsbreedteklasse" |
			
			
							

#### Domein "WE\_verhardingsbreedteklasse"

| Domein | WE\_verhardingsbreedteklasse |
|:---|:---|
| Domeinwaarde | **> 7 meter** |
| Definitie | De breedte van de verharding, inclusief beton- en klinkerrand op gelijk niveau als het wegdek, berijdbare goot, geintegreerde rijwielstrook en/of busbaan en parkeerstrook is 7 meter of meer. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_verhardingsbreedteklasse |
|:---|:---|
| Domeinwaarde | **4 - 7 meter** |
| Definitie | De breedte van de verharding, inclusief beton- en klinkerrand op gelijk niveau als het wegdek, berijdbare goot, geintegreerde rijwielstrook en/of busbaan en parkeerstrook is 4 meter of breder en smaller dan 7 meter. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_verhardingsbreedteklasse |
|:---|:---|
| Domeinwaarde | **2 - 4 meter** |
| Definitie | De breedte van de verharding, inclusief beton- en klinkerrand op gelijk niveau als het wegdek, berijdbare goot, geintegreerde rijwielstrook en/of busbaan en parkeerstrook is 2 meter of breder en smaller dan 4 meter. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_verhardingsbreedteklasse |
|:---|:---|
| Domeinwaarde | **< 2 meter** |
| Definitie | De breedte van de verharding, inclusief beton- en klinkerrand op gelijk niveau als het wegdek, berijdbare goot is smaller dan 2 meter. |
						 
| Inwinningscriteria | Een verhardingsbreedteklasse "< 2 meter" geldt alleen voor weglijnen. |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Nee |
							

### Attribuut gescheiden rijbaan

| Attribuut | gescheiden rijbaan |
|:---|:---|
| Definitie | Aanduiding of het object onderdeel uitmaakt van een weg met gescheiden rijbanen. |
| Inwinningscriteria | Een weg heeft gescheiden rijbanen als het obstakel (vangrail, verhoogde betonrand, middenberm) tussen de rijbanen langer is dan 500 meter, mits beide wegen als een samenhangend geheel kunnen worden beschouwd. Een plaatselijke onderbreking van het obstakel (bijvoorbeeld bij een brug) wordt niet als onderbreking van het obstakel beschouwd. In het geval het terrein tussen beide rijbanen gevuld is met min of meer aaneengesloten bebouwing of met water of met een dusdanige dichte begroeiing dat het verband tussen beide wegen in het terrein niet meer is waar te nemen dan worden beide rijbanen niet meer aangegeven als gescheiden rijbaan.<br>De combinatie van gescheiden rijbaan "ja" en straat is niet toegestaan. |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "WE\_gescheidenRijbaan" |
			
			
							

#### Domein "WE\_gescheidenRijbaan"

| Domein | WE\_gescheidenRijbaan |
|:---|:---|
| Domeinwaarde | **ja** |
| Definitie | Het object maakt deel uit van een weg met gescheiden rijbanen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_gescheidenRijbaan |
|:---|:---|
| Domeinwaarde | **nee** |
| Definitie | Het object maakt geen deel uit van een weg met gescheiden rijbanen. |
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

### Attribuut verhardingstype

| Attribuut | verhardingstype |
|:---|:---|
| Definitie | Het type verharding van een wegdeel. |
																								 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "WE\_verhardingsType" |
							

#### Domein "WE\_verhardingsType"

| Domein | WE\_verhardingsType |
|:---|:---|
| Domeinwaarde | **verhard** |
| Definitie | Een weg met een egale verharding (asfalt, beton, klinkers, tegels, keien, etc.). |
| Inwinningscriteria | Ook wegen met een verharding in slechte staat worden als verhard ingewonnen. Wegen die van nature min of meer steenachtig zijn, zoals bijvoorbeeld in Limburg, worden als onverhard aangegeven. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_verhardingsType |
|:---|:---|
| Domeinwaarde | **half verhard** |
| Definitie | Een weg waarop de verharding slechts gedeeltelijk is aangebracht (als twee banen met klinkers, beton, tegels, of uitsluitend groenstenen, etc.) of het rijvlak is verbeterd met grind of sintels. |
| Inwinningscriteria | Wegen met een verharding in slechte staat worden als verhard ingewonnen. Wegen die van nature min of meer steenachtig zijn, zoals bijvoorbeeld in Limburg, worden als onverhard aangegeven. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_verhardingsType |
|:---|:---|
| Domeinwaarde | **onverhard** |
| Definitie | Een weg zonder enige vorm van kunstmatige verharding, dan wel een weg hier en daar opgevuld met puin. |
| Inwinningscriteria | Ook wegen die van nature min of meer steenachtig zijn, zoals bijvoorbeeld in Limburg, worden als onverhard aangegeven. |
						 
| Volledigheid | Volledig |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_verhardingsType |
|:---|:---|
| Domeinwaarde | **onbekend** |
| Definitie | De waarde van het objectkenmerk is niet bekend. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

### Attribuut aantal rijstroken

| Attribuut | aantal rijstroken |
|:---|:---|
| Definitie | Het aantal onderverdelingen van een wegdeel d.m.v. strepen, verschil in verharding of kleur. |
| Inwinningscriteria | Wordt aangegeven voor alle wegdelen behorende tot de categorie autosnelwegen en/of hoofdwegen. Niet meegeteld worden geïntegreerde stroken met een speciale bestemming zoals busbaan en rijwielstrook. Een eventuele wisselstrook (een fysiek gescheiden rijbaan die beurtelings per rijrichting gebruikt wordt om doorstroming van het verkeer in de spits te bevorderen) telt mee voor het aantal rijstroken. Een wisselend aantal rijstroken wordt pas weergegeven als het aantal rijstroken over tenminste 500 m constant is. Bij een weg met gescheiden rijbanen wordt het **aantal rijstroken** per rijbaan aangegeven. Het **aantal rijstroken** wordt _**niet**_ toegevoegd aan op- en afritten, wel aan de verbindingswegen op een **knooppunt**. |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
					
| Optionaliteit | Optioneel |
| Formaat | Geheel getal |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut naam

| Attribuut | naam |
|:---|:---|
| Definitie | De naam van het wegdeel. |
| Inwinningscriteria | De naam van het wegdeel is gebaseerd op informatie uit de Basisregistratie Adressen en Gebouwen (BAG).<br>De tekst "Veerdienst … - …" mag opgenomen worden bij een wegdeel veerverbinding. De naam moet beide plaatsen bevatten. |
| Volledigheid | Beperkt |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut isBAGnaam

| Attribuut | isBAGnaam |
|:---|:---|
| Definitie | Aanduiding of de naam geverifieerd is met de BAG. |
| Inwinningscriteria | Wegen van het type kruising hebben geen aanduiding 'isBAGnaam'. |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Domein | "WE\_isBAGnaam" |
			
			
							

#### Domein "WE\_isBAGnaam"

| Domein | WE\_isBAGnaam |
|:---|:---|
| Domeinwaarde | **ja** |
| Definitie | De naam is geverifieerd met de BAG. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

| Domein | WE\_isBAGnaam |
|:---|:---|
| Domeinwaarde | **nee** |
| Definitie | De naam is niet geverifieerd met de BAG. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
							

### Attribuut A-wegnummer

| Attribuut | A-wegnummer |
|:---|:---|
| Definitie | Nummering van de rijkswegen (autosnelwegen en autowegen) behorende tot het nationale wegenstelsel. |
| Inwinningscriteria | Wordt opgenomen voor alle betreffende wegdelen, inclusief op- en afritten.<br>In incidentele gevallen komt het voor dat een autosnelweg tijdelijk overgaat in een autoweg waarbij het A-wegnummer blijft doorlopen. In die gevallen is het toegestaan aan de autoweg het betreffende A-wegnummer toe te voegen. |
| Volledigheid | Volledig |
| Multipliciteit | Veelvoudig |
					
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut N-wegnummer

| Attribuut | N-wegnummer |
|:---|:---|
| Definitie | Nummering van de provinciale wegen behorende tot het nationale wegenstelsel en nummering van rijkswegen die nog niet de status van autosnelweg hebben. |
| Inwinningscriteria | Wordt opgenomen voor alle betreffende wegdelen, inclusief op- en afritten.<br>Bij een kruising van twee wegen met N-wegnummering over een rotonde krijgen alle wegdelen van de rotonde een dubbel N-wegnummer. Dit geldt niet indien het een T-splitsing betreft. In dat geval krijgen de wegdelen op de rotonde enkel het doorgaande N-wegnummer. |
| Volledigheid | Volledig |
| Multipliciteit | Veelvoudig |
					
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut E-wegnummer

| Attribuut | E-wegnummer |
|:---|:---|
| Definitie | Nummering van rijkswegen behorende tot het stelsel van europese doorgaande routes. |
| Inwinningscriteria | Wordt opgenomen voor alle betreffende wegdelen, echter niet aan de wegdelen behorende tot de op- en afritten, tenzij deze behoren tot de E-route of een verbinding vormen tussen verschillende E-routes. |
| Volledigheid | Volledig |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut S-wegnummer

| Attribuut | S-wegnummer |
|:---|:---|
| Definitie | Nummering van secundaire wegen behorende tot het provinciale wegenstelsel. |
| Inwinningscriteria | Wordt opgenomen voor alle betreffende wegdelen, inclusief op- en afritten. |
| Volledigheid | Volledig |
| Multipliciteit | Veelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut afritnummer

| Attribuut | afritnummer |
|:---|:---|
| Definitie | Afritnummering op autosnelweg en hoofdweg, vastgesteld door Rijkswaterstaat. |
									 
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut afritnaam

| Attribuut | afritnaam |
|:---|:---|
| Definitie | Afritbenaming op autosnelweg, vastgesteld door Rijkswaterstaat. |
| Inwinningscriteria | Wordt (nog) niet ingewonnen. |
| Volledigheid | Niet |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut knooppuntnaam

| Attribuut | knooppuntnaam |
|:---|:---|
											 
| Definitie | Naam van een knooppunt. |
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut brugnaam

| Attribuut | brugnaam |
|:---|:---|
| Definitie | De naam van een brug. |
| Inwinningscriteria | Indien de brug is gelegen over een waterdeel van het type Greppel, Enkele sloot of Gerenforceerde sloot en er zich geen weer te geven brugvlak boven het waterdeel bevindt is het niet mogelijk een naam toe te voegen. Indien de brug wel is beschreven op de 1:25.000 wordt in dat geval een inrichtingspunt geplaatst van het type overig waaraan de naam wordt toegevoegd. |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut tunnelnaam

| Attribuut | tunnelnaam |
|:---|:---|
| Definitie | Naam van een tunnel. |
																																																																					 
						 
| Inwinningscriteria | - |
| Volledigheid | Beperkt |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Optioneel |
| Formaat | Tekst |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |

### Attribuut status

| Attribuut | status |
|:---|:---|
| Definitie | De staat waarin het object zich bevindt. |
																										 
						 
| Inwinningscriteria | - |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Tekst |
| Domein | "Status" |
							

### Attribuut hoogteniveau

| Attribuut | hoogteniveau |
|:---|:---|
| Definitie | Met het hoogteniveau wordt de relatieve hoogte van het geo-object weergegeven. Zo kan worden bepaald op welke wijze geo-objecten elkaar kruisen. |
																																		 
						 
| Inwinningscriteria | - |
| Volledigheid | Volledig |
| Multipliciteit | Enkelvoudig |
| Optionaliteit | Verplicht |
| Formaat | Geheel getal |
| Domein | ≤ 0 (0, -1, -2, -3, …) |
| Punt | Ja |
| Lijn | Ja |
| Vlak | Ja |
