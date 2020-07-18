---
layout: default
title: iPhone se
path: 1
---

<div class="container">
  <h3>{{ page.title }}</h3>
  {% for phone-list in site.data.smartphones %}
  {% assign phone = phone-list[1] %}
  <h4>{{ phone.name }}</h4>
  {% endfor %}
  crapz
</div>
