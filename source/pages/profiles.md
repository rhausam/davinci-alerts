---
title: Profiles defined as part of this Guide
layout: default
active: profiles
---
### Resource Profiles

The following Profiles for FHIR *resources* have been defined for this implementation guide.

{% include list-profiles.xhtml %}

<br />

<!-- {% raw %}
### Datatype Profiles

The following Profiles for FHIR *datatypes* have been defined for this implementation guide.

{% for sd_hash in site.data.structuredefinitions -%}
  {%- assign sd = sd_hash[1] -%}
  {%- if sd.kind  == "complex-type" and sd.type != "Extension" -%}
    - [{{sd.name}}]  ({{sd.path}})
  {%- endif -%}
{%- endfor -%}

<br />

### Extensions

These extensions have been defined for this implementation guide.


{% include list-extensions.xhtml %}

{% endraw %} -->

{% include link-list.md %}
