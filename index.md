---
layout: default
---
![Banner](/assets/images/banner_index.jpg){: style="width: 100%;"}

## Produtos em destaque

{% for product in site.destaque %}
<div>
  <a href="{{ product.url | relative_url }}">
  {% include products.html %}
  </a>
</div>
{% endfor %}
