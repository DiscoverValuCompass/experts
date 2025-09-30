---
title: "Legal"
parent: "External"
has_children: true
nav_order: 30
---
# Legal (External)
Profiles of external legal professionals.

<!-- BEGIN: expert-list external/legal (auto-generated) -->
<ul>
{% for e in site.experts %}
  {% if e.group == "external" and e.categories contains "legal" %}
    <li><a href="{{ e.url | relative_url }}">{{ e.name }}</a> — {{ e.title }}</li>
  {% endif %}
{% endfor %}
</ul>
<!-- END: expert-list external/legal -->
