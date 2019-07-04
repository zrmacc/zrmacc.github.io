---
layout: single
title: Statistics
permalink: /Collections/Statistics/
sidebar: 
 nav: "navi"
---

{% for page in site.statistics %}
  <h4>
  	<a href="{{ page.url }}">{{ page.title }}</a>
  </h4>
{% endfor %}
