---
layout: page
title: breakfast
permalink: /breakfast/
header: true

---

<ul>
{% for recipe in site.breakfast %}
  <li>
    {{ <a href="{{ recipe.url }}">{{ recipe.title }}</a>
  </li>
{% endfor %}
</ul>
