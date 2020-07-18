---
layout: default
title: iPhone se
---

<div class="container">
  <h3>olla</h3>
  {% for phones in site.data.smartphones %}
  {% assign phone = phones %}
  <h4>{{ phone.name }}</h4>
  {% endfor %}
</div>
