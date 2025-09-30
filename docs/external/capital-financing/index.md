---
title: "Capital & Financing"
parent: "External"
has_children: true
nav_order: 50
---
# Capital & Financing (External)
Profiles of external capital/financing professionals.

<!-- BEGIN: expert-list external/capital-financing (auto-generated) -->
<ul>
{% for e in site.experts %}
  {% if e.group == "external" and e.categories contains "capital-financing" %}
    <li><a href="{{ e.url | relative_url }}">{{ e.name }}</a> — {{ e.title }}</li>
  {% endif %}
{% endfor %}
</ul>
<!-- END: expert-list external/capital-financing -->
