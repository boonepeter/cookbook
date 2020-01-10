---
layout: page
title: Posts
permalink: cookbook/dinner/
header: true

---

<ul>
{% for recipe in site.dinner %}
  <li>
    {{ <a href="{{ recipe.url }}">{{ recipe.title }}</a>
  </li>
{% endfor %}
</ul>
