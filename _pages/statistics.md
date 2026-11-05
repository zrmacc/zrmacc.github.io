---
layout: single
title: Statistics
permalink: /Collections/Statistics/
sidebar:
  nav: "navi"
---

{% assign notes = site.statistics | sort: "title" %}

<section class="collection-section">
  <h2>Asymptotics</h2>
  {% include note-list.html notes=notes category="Asymptotics" %}
</section>

<section class="collection-section">
  <h2>Applied</h2>
  {% include note-list.html notes=notes category="Applied" %}
</section>

<section class="collection-section">
  <h2>Inference</h2>
  {% include note-list.html notes=notes category="Inference" %}
</section>

<section class="collection-section">
  <h2>Mathematical</h2>
  {% include note-list.html notes=notes category="Mathematics" %}
</section>

<section class="collection-section">
  <h2>Methods</h2>
  {% include note-list.html notes=notes category="Methods" %}
</section>
