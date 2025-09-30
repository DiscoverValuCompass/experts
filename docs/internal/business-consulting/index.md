---
title: "Business Consulting"
parent: "Internal"
has_children: true
nav_order: 40
---
# Business Consulting (Internal)
Profiles of internal business consultants.

<!-- BEGIN: expert-list internal/business-consulting (auto-generated) -->
<ul>
{% for e in site.experts %}
  {% if e.group == "internal" and e.categories contains "business-consulting" %}
    <li><a href="{{ e.url | relative_url }}">{{ e.name }}</a> — {{ e.title }}</li>
  {% endif %}
{% endfor %}
</ul>
<!-- END: expert-list internal/business-consulting -->
