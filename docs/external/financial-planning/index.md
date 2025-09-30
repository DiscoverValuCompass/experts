---
title: "Financial Planning"
parent: "External"
has_children: true
nav_order: 60
---
# Financial Planning (External)
Profiles of external financial planners.

<!-- BEGIN: expert-list external/financial-planning (auto-generated) -->
<ul>
{% for e in site.experts %}
  {% if e.group == "external" and e.categories contains "financial-planning" %}
    <li><a href="{{ e.url | relative_url }}">{{ e.name }}</a> — {{ e.title }}</li>
  {% endif %}
{% endfor %}
</ul>
<!-- END: expert-list external/financial-planning -->
