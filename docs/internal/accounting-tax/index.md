---
title: "Accounting / Tax"
parent: "Internal"
has_children: true
nav_order: 10
---
# Accounting / Tax (Internal)
Profiles of internal accounting & tax experts.

<ul>
{% for e in site.experts %}
  {% if e.group == "internal" and e.categories contains "accounting-tax" %}
    <li><a href="{{ e.url | relative_url }}">{{ e.name }}</a> — {{ e.title }}</li>
  {% endif %}
{% endfor %}
</ul>