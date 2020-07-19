---
layout: default
title: Apple
brand: apple
---

<div class="container">
  {% assign phone-by-brand = site.smartphones | where: "brand", "apple" %}
  {% for phone in phone-by-brand %}
  <li>{{ phone.title }}</li>
  {% endfor %}
</div>
