---
layout: default
title: iphone se
---

<div class="container">
  <h3>ola</h3>
  {% for phone in site.data.smartphones.apple.iphone-se %}
  <h4>{{ phone.name }}</h4>
  {% endfor %}
</div>
