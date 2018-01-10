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
 

 This page describes my projects briefly. Please follow the hyperlink for an in detail description. The links to code or the paper are available wherever possible.

<ul style="list-style:none;padding-left:0;margin:0">
  {% for post in site.posts %}
  {% assign cat = post.categories | first %}
  {% if cat == "Research" %}
    <li>
      <h3><b><a href="{{ post.url }}" style="color:black;">{{ post.title }}</a></b></h3>
      <font color="silver"><i>{{post.head}}</i> </font>
      <br>
      {{post.summary}}
    </li>
    <br>
    <hr>
    <br>
  {% endif %}
  {% endfor %}
</ul>

More information will be updated soon.