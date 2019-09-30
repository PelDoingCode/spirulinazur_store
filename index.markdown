---
title: Spirulinazur
layout: default
header-img: "assets/logo_figma.png"
subtitle:   "Parce que la nature a déjà tout prévu."

---

<!-- {% for product in site.products %}
  {% include product.html %}
{% endfor %} -->


<div class="text-color">

  <h3> Spiruline,  le super-aliment pour booster votre <br> énergie toute la journée.</h3>

  <h4> Laissez-nous prendre soin de vous. </h4>

  {% for product in site.products %}
    {% include product.html %}
  {% endfor %}

</div>
