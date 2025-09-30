---
title: "Financial Planning"
parent: "Internal"
has_children: true
nav_order: 60
---
# Financial Planning (Internal)
Profiles of internal financial planners.

<!-- BEGIN: expert-list internal/financial-planning (auto-generated) -->
<ul>
{% for e in site.experts %}
  {% if e.group == "internal" and e.categories contains "financial-planning" %}
    <li><a href="{{ e.url | relative_url }}">{{ e.name }}</a> — {{ e.title }}</li>
  {% endif %}
{% endfor %}
</ul>
<!-- END: expert-list internal/financial-planning -->
