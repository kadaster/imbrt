<!---
Deze readme.md wordt gebruikt om de catalogus en productspecificaties via GIThub Pages te ontsluiten als https://kadaster.github.io/imbrt/
-->
{% capture my_include %}{% include_relative catalogus-productspecificaties.md %}{% endcapture %}
{{ my_include | markdownify }}
{% capture my_include %}{% include_relative catalogus_waardelijsten.md %}{% endcapture %}
{{ my_include | markdownify }}
{% capture my_include %}{% include_relative mutatieprotocol.md %}{% endcapture %}
{{ my_include | markdownify }}
