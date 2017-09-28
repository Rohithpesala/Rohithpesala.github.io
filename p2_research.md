---
layout: page
title: Research
permalink: /research/
---

<!-- {% for category in site.categories %}
  {% assign cat = category | first %}
  {% if cat == "Research" %}
  <li><a name="{{ category | first }}">{{ cat }}</a>
    <ul>
    {% for posts in category %}
      {% for post in posts %}
        <li><a href="{{ post.url }}">{{ post.title }}</a></li>
      {% endfor %}
    {% endfor %}
    </ul>
  </li>
  {% endif %}

{% endfor %}
 -->
<h1>Research  </h1>
 

 Here, I describe my projects more in detail than in the resume. Code for all projects isn't available or in some cases confidential. I have provided links to git repos of whatever code I have already written

<ul>
  {% for post in site.posts %}
  {% assign cat = post.categories | first %}
  {% if cat == "Research" %}
    <li>
      <a href="{{ post.url }}">{{ post.title }}</a>
      {{post.summary}}
    </li>
  {% endif %}
  {% endfor %}
</ul>

More information will be updated soon.