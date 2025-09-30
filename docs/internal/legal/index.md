---
title: "Legal"
parent: "Internal"
has_children: true
nav_order: 30
---
# Legal (Internal)
Profiles of internal legal experts.

<!-- BEGIN: expert-list internal/legal (auto-generated) -->
<ul>
{% for e in site.experts %}
  {% if e.group == "internal" and e.categories contains "legal" %}
    <li><a href="{{ e.url | relative_url }}">{{ e.name }}</a> — {{ e.title }}</li>
  {% endif %}
{% endfor %}
</ul>
<!-- END: expert-list internal/legal -->
