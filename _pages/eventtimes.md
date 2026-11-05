---
layout: single
title: Event Times
permalink: /Collections/Eventtimes/
sidebar:
  nav: "navi"
---

{% assign notes = site.eventtimes | sort: "title" %}

<section class="collection-section">
  <h2>Stochastic Process</h2>
  {% include note-list.html notes=notes category="Stochastic" %}
</section>

<section class="collection-section">
  <h2>Survival</h2>
  {% include note-list.html notes=notes category="Survival" %}
</section>
