---
title: "Wealth Management / AUM"
parent: "External"
has_children: true
nav_order: 90
---
# Wealth Management / AUM (External)
Profiles of external wealth management/AUM professionals.

<!-- BEGIN: expert-list external/wealth-management-aum (auto-generated) -->
<ul>
{% for e in site.experts %}
  {% if e.group == "external" and e.categories contains "wealth-management-aum" %}
    <li><a href="{{ e.url | relative_url }}">{{ e.name }}</a> — {{ e.title }}</li>
  {% endif %}
{% endfor %}
</ul>
<!-- END: expert-list external/wealth-management-aum -->
