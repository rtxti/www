---
layout: default
title: iPhone se
---

<div class="container">
  <h3>olla</h3>
  {% for phone in site.data.smartphones.iphone-se %}
  <h4>{{ phone.name }}</h4>
  {% endfor %}
</div>
