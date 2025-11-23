---
layout: single
title: Event Times
permalink: /Collections/Eventtimes/
sidebar: 
 nav: "navi"
---

<!-- 
<ul>: Unordered list; <li>: list item.
 -->

{% assign sortedPages = site.eventtimes | sort: 'title' %}


<h2 style="font-size:1.20em"> Stochastic Process </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Stochastic' %}
<h3 style="font-size:0.75em">
<ul>
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
</ul>
</h3>
	{% endif %}
{% endfor %}

<h2 style="font-size:1.20em"> Survival </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Survival' %}
<h3 style="font-size:0.75em">
<ul>
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
</ul>
</h3>
	{% endif %}
{% endfor %}