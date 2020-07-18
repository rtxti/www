---
layout: default
title: iphone se
---

<div class="container">
  <h3>olla</h3>
  {% for phones in site.data.smartphones.apple %}
  {% assign phone = phones[1] %}
  <h4>{{ phone.name }}</h4>
  {% endfor %}
</div>
