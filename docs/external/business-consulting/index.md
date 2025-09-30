---
title: "Business Consulting"
parent: "External"
has_children: true
nav_order: 40
---
# Business Consulting (External)
Profiles of external business consultants.

<!-- BEGIN: expert-list external/business-consulting (auto-generated) -->
<ul>
{% for e in site.experts %}
  {% if e.group == "external" and e.categories contains "business-consulting" %}
    <li><a href="{{ e.url | relative_url }}">{{ e.name }}</a> — {{ e.title }}</li>
  {% endif %}
{% endfor %}
</ul>
<!-- END: expert-list external/business-consulting -->
