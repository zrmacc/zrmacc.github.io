---
layout: single
title: Statistics
permalink: /Collections/Statistics/
sidebar: 
 nav: "navi"
---

{% assign sortedPages = site.statistics | sort: 'title' %}

<h2> Inference </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Inference' %}
<h4>
	<a href="{{ page.url }}">{{ page.title }}</a>
</h4>
	{% endif %}
{% endfor %}

<h2> Regression </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Regression' %}
<h4>
	<a href="{{ page.url }}">{{ page.title }}</a>
</h4>
	{% endif %}
{% endfor %}