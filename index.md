---
layout: default
---
![Banner](https://1.bp.blogspot.com/-CAVEZkFt2Os/YE6YdesajJI/AAAAAAAAIDQ/VzAnVXCblfUcXBRnvCsrEr7lVzco9W36ACLcBGAsYHQ/s0/banner_index.jpg){: style="width: 100%;"}

## Chegaram as [camisetas](https://lojanoise.netlify.app/camiseta/){: style="color: black; text-decoration: none; text-transform: uppercase; font-weight: bold; font-family: Arial, Helvetica, sans-serif; font-size: large;"}!

## Não deixem de checar os [E-books gratuitos](https://lojanoise.netlify.app/ebook/){: style="color: black; text-decoration: none; text-transform: uppercase; font-weight: bold; font-family: Arial, Helvetica, sans-serif; font-size: large;"}!

{% for product in site.destaque %}
<div>
  <a href="{{ product.url | relative_url }}">
  {% include products.html %}
  </a>
</div>
{% endfor %}
