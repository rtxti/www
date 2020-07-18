---
layout: default
title: iphone se
---

<div class="container">
  <h3>holla</h3>
  {% assign phones = site.data.smartphones.apple.iphone-se %}
  {% for phone in phones %}
  <h4>{{ phone.name }}</h4>
  {% endfor %}
</div>
