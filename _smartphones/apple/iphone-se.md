---
layout: default
title: iPhone se
path: 1
---

<div class="container">
  <h3>{{ page.title }}</h3>
  {% for phone in site.data.smartphones[page.path] %}
  <h4>{{ phone.name }}</h4>
  {% endfor %}
  crapz
</div>
