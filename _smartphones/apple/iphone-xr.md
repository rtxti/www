---
layout: default
title: iPhone xr
---

<div class="container">
  <h3>olla</h3>
  {% for phones in site.data.smartphones.apple %}
  {% assign phone = phones %}
  <h4>{{ phone.name }}</h4>
  {% endfor %}
</div>
