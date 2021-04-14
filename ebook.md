---
layout: default
---
![Banner](https://1.bp.blogspot.com/-k_aBrRpkhT4/YHYxaSGh_zI/AAAAAAAAILo/qf3UKuXS8q0G3tYujORpJjvN3sX2VTSDwCLcBGAsYHQ/s2000/banner%2Bebooks.jpg){: style="width: 100%;"}
{% for product in site.ebook %}
<div>
  <a href="{{ product.url | relative_url }}">
  {% include ebook.html %}
  </a>
</div>
{% endfor %}
