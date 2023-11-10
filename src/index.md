---
title: Hello Worlds
layout: "base.njk"
---

Hello Jamstack fam!!

<ul>
{% for post in collections.posts %}
  <li><a href="{{ post.url }}">{{ post.data.title }}</a></li>
{% endfor %}
</ul>
