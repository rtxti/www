---
layout: default
title: iPhone se
path: 1
---

<div class="container">
  <h3>{{ page.title }}</h3>
  {% for phones in site.data.smartphones %}
  {% assign phone = phones[1] %}
  <h4>{{ phone.release }}</h4>
  {% endfor %}
  craps
</div>
