---
layout: single
title: Genetics
permalink: /Collections/Genetics/
sidebar: 
 nav: "navi"
---

<!-- 
<ul>: Unordered list; <li>: list item.
 -->

{% assign sortedPages = site.genetics | sort: 'title' %}

<h2 style="font-size:1.20em"> Genetics </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Genetics' %}
<h3 style="font-size:0.75em">
<ul>
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
</ul>
</h3>
	{% endif %}
{% endfor %}
