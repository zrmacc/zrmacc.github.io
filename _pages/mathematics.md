---
layout: single
title: Mathematics
permalink: /Collections/Mathematics/
sidebar: 
 nav: "navi"
---

<!-- 
<ul>: Unordered list; <li>: list item.
 -->

{% assign sortedPages = site.mathematics | sort: 'title' %}


<h2 style="font-size:1.20em"> Mathematics </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Mathematics' %}
<h3 style="font-size:0.75em">
<ul>
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
</ul>
</h3>
	{% endif %}
{% endfor %}