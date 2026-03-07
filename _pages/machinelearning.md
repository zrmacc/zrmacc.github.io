---
layout: single
title: Machine Learning
permalink: /Collections/Machinelearning/
sidebar: 
 nav: "navi"
---

<!-- 
<ul>: Unordered list; <li>: list item.
 -->

{% assign sortedPages = site.machinelearning | sort: 'title' %}

<h2 style="font-size:1.20em"> Machine Learning </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Machinelearning' %}
<h3 style="font-size:0.75em">
<ul>
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
</ul>
</h3>
	{% endif %}
{% endfor %}
