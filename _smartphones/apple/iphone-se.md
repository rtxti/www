---
layout: default
title: iPhone se
path: 1
---

<div class="container">
  <h3>{{ page.title }}</h3>
  {% for phones in site.data.smartphones %}
  {% assign phone = phones %}
  <h4>{{ phone.name }}</h4>
  {% endfor %}
  crapz
</div>
