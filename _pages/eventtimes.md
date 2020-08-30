---
layout: single
title: Event Times
permalink: /Collections/Eventtimes/
sidebar: 
 nav: "navi"
---

{% assign sortedPages = site.eventtimes | sort: 'title' %}

<h2> Implementation </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Implementation' %}
<h4>
	<a href="{{ page.url }}">{{ page.title }}</a>
</h4>
	{% endif %}
{% endfor %}

<h2> Stochastic Process </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Stochastic' %}
<h4>
	<a href="{{ page.url }}">{{ page.title }}</a>
</h4>
	{% endif %}
{% endfor %}

<h2> Survival </h2>
{% for page in sortedPages %}
	{% if page.categories contains 'Survival' %}
<h4>
	<a href="{{ page.url }}">{{ page.title }}</a>
</h4>
	{% endif %}
{% endfor %}