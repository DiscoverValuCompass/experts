---
title: "Capital & Financing"
parent: "Internal"
has_children: true
nav_order: 50
---
# Capital & Financing (Internal)
Profiles of internal capital/financing experts.

<!-- BEGIN: expert-list internal/capital-financing (auto-generated) -->
<ul>
{% for e in site.experts %}
  {% if e.group == "internal" and e.categories contains "capital-financing" %}
    <li><a href="{{ e.url | relative_url }}">{{ e.name }}</a> — {{ e.title }}</li>
  {% endif %}
{% endfor %}
</ul>
<!-- END: expert-list internal/capital-financing -->
