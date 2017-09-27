---
layout: page
title: Research
permalink: /research/
---

<ul>
  {% for post in site.about %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{post.content}}
    </li>
  {% endfor %}
</ul>

More information will be updated soon.