---
layout: single
title: Scientific Software
permalink: /Software/
classes: wide
description: Open-source statistical methods and scientific software developed by Zachary McCaw.
header:
  overlay_image: /assets/images/portfolio/software-caldera.jpeg
  overlay_filter: 0.38
  caption: Caldera, Santorini, Greece.
---

<div class="portfolio-page software-page" markdown="1">

Open-source R packages implementing statistical methodology.

<div class="software-grid">
{% for project in site.data.software %}
  <article class="software-card">
    <p class="eyebrow">{{ project.domain }}</p>
    <h2><a href="{{ project.url }}">{{ project.name }}</a></h2>
    <p>{{ project.description }}</p>
    {% if project.papers %}
    <p class="software-card__links">
      {% for paper in project.papers %}<a href="{{ paper.url }}">{{ paper.label }}</a>{% unless forloop.last %}<span aria-hidden="true"> · </span>{% endunless %}{% endfor %}
    </p>
    {% endif %}
  </article>
{% endfor %}
</div>

</div>
