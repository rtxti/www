---
layout: default
title: iPhone se
path: iphone-se
---

<div class="container">
  <h3>{{ page.title }}</h3>
  {% assign phone = site.data.smartphones[page.path] %}
  <h4>{{ phone.release }}</h4>
</div>
