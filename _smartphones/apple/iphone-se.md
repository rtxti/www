---
layout: default
title: iphone se
---

<div class="container">
  <h3>holla</h4>
  {% assign phones = site.data.smartphone.apple.iphone-se %}
  {% for phone in phones %}
  <h4>{{ phone.name }}</h4>
  {% endfor %}
</div>
