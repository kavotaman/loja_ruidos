---
layout: default
---
# Bem Vindo à Noise, a loja mais ruidosa da Via Láctea!
{% for product in site.camiseta %}
  {% include camiseta.html %}
{% endfor %}
{% for product in site.perecoteco %}
  {% include perecoteco.html %}
{% endfor %}
{% for product in site.bastidor %}
  {% include bastidor.html %}
{% endfor %}
