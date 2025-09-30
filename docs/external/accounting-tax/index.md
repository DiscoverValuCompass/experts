---
title: "Accounting / Tax"
parent: "External"
has_children: true
nav_order: 10
permalink: /external/accounting-tax/
---
# Accounting / Tax (External)
Profiles of external accounting & tax professionals.


<!-- BEGIN: expert-list external/accounting-tax (auto-generated) -->
<ul>
{% for e in site.experts %}
  {% if e.group == "external" and e.categories contains "accounting-tax" %}
    <li><a href="{{ e.url | relative_url }}">{{ e.name }}</a> — {{ e.title }}</li>
  {% endif %}
{% endfor %}
</ul>
<!-- END: expert-list external/accounting-tax -->
