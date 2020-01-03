---
layout: single
title: Statistics
permalink: /Collections/Statistics/
sidebar: 
 nav: "navi"
---

{% assign sortedPages = site.statistics | sort: 'title' %}

<h2> Asymptotics </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Asymptotics' %}
<h4>
	<a href="{{ page.url }}">{{ page.title }}</a>
</h4>
	{% endif %}
{% endfor %}

<h2> Inference </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Inference' %}
<h4>
	<a href="{{ page.url }}">{{ page.title }}</a>
</h4>
	{% endif %}
{% endfor %}

<h2> Mathematical </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Mathematical' %}
<h4>
	<a href="{{ page.url }}">{{ page.title }}</a>
</h4>
	{% endif %}
{% endfor %}

<h2> Methods </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Methods' %}
<h4>
	<a href="{{ page.url }}">{{ page.title }}</a>
</h4>
	{% endif %}
{% endfor %}