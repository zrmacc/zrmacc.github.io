---
layout: single
title: Statistics
permalink: /Collections/Statistics/
sidebar: 
 nav: "navi"
---

<!-- 
<ul>: Unordered list; <li>: list item.
 -->

{% assign sortedPages = site.statistics | sort: 'title' %}

<h2 style="font-size:1.20em"> Asymptotics </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Asymptotics' %}
<h3 style="font-size:0.75em">
<ul>
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
</ul>
</h3>
	{% endif %}
{% endfor %}

<h2 style="font-size:1.20em"> Applied </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Applied' %}
<h3 style="font-size:0.75em">
<ul>
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
</ul>
</h3>
	{% endif %}
{% endfor %}

<h2 style="font-size:1.20em"> Inference </h2>
{% for page in sortedPages %}
	 {% if page.categories contains 'Inference' %}
<h3 style="font-size:0.75em">
<ul>
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
</ul>
</h3>
	{% endif %}
{% endfor %}

<h2 style="font-size:1.20em"> Mathematical </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Mathematics' %}
<h3 style="font-size:0.75em">
<ul>
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
</ul>
</h3>
	{% endif %}
{% endfor %}

<h2 style="font-size:1.20em"> Methods </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Methods' %}
<h3 style="font-size:0.75em">
<ul>
	<li><a href="{{ page.url }}">{{ page.title }}</a></li>
</ul>
</h3>
	{% endif %}
{% endfor %}