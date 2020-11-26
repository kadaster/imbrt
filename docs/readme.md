<!---
Deze readme.md wordt gebruikt om de catalogus en productspecificaties via GIThub Pages te ontsluiten
-->
{% capture my_include %}{% include_relative catalogus-productspecificaties.md %}{% endcapture %}
{{ my_include | markdownify }}