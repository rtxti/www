---
layout: default
title: iPhone se
---

<div class="container">
  <h3>holla</h3>
  {% for phone in site.data.smartphones.iphone-se %}
  <h4>{{ phone.release }}</h4>
  {% endfor %}
</div>
