---
layout: archive
title: "SVG"
permalink: /svg/
author_profile: ture
---

{% include base_path %}

{% for item in site.my_collection %}
  <h2>{{ item.title }}</h2>
  <p>{{ item.description }}</p>
  <p><a href="{{ item.url }}">{{ item.title }}</a></p>
  
{% for post in site.svg %}
  {% include archive-single.html %}
{% endfor %}