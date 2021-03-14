---
layout: default
---
# Decoração

{% for product in site.decoracao %}
<div>
  <a href="{{ product.url | relative_url }}">
  {% include products.html %}
  </a>
</div>
{% endfor %}
