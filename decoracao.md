---
layout: default
---
![Banner](https://1.bp.blogspot.com/-B2Mwcs5o8mA/YE6YdXBOfaI/AAAAAAAAIDU/hk26xeXSb7M5dbdvQxf26T4NAImRBDL3QCLcBGAsYHQ/s0/banner%2Bdecora%25C3%25A7%25C3%25A3o.jpg){: style="width: 100%;"}
{% for product in site.decoracao %}
<div>
  <a href="{{ product.url | relative_url }}">
  {% include products.html %}
  </a>
</div>
{% endfor %}
