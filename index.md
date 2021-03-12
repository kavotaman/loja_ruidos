---
layout: default
---
<style>
/* Create three equal columns that floats next to each other */
.column {
  float: left;
  width: 25%;
  padding: 15px;
}

/* Clear floats after the columns */
.row:after {
  content: "";
  display: table;
  clear: both;
}

/* Responsive layout - makes the three columns stack on top of each other instead of next to each other */
@media screen and (max-width:600px) {
  .column {
    width: 100%;
  }
}
</style>
# Bem Vindo à Noise, a loja mais ruidosa da Via Láctea!
{% for product in site.camiseta %}
  {% include products_index.html %}
{% endfor %}
{% for product in site.perecoteco %}
  {% include products_index.html %}
{% endfor %}
{% for product in site.bastidor %}
  {% include products_index.html %}
{% endfor %}
