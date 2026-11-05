---
layout: single
title: Selected Research
permalink: /Research/
classes: wide
description: Selected research in machine learning, statistical genetics, and biostatistics.
header:
  overlay_image: /assets/images/portfolio/research-desert.jpeg
  overlay_filter: 0.38
  caption: Badlands, Death Valley, CA.
---

<div class="portfolio-page research-page" markdown="1">

Research spanning machine learning, statistical genetics, and biostatistics. A complete publication record is available through [Google Scholar](https://scholar.google.com/citations?user=lYRkHs8AAAAJ&hl=en) and the [CV](/CV/).

{% for group in site.data.research %}
<section class="research-group" id="{{ group.slug }}">
  <header class="section-heading">
    <p class="eyebrow">Selected Research</p>
    <h2>{{ group.name }}</h2>
    <p>{{ group.description }}</p>
  </header>

  <div class="publication-list">
    {% for paper in group.papers %}
    <article class="publication-item">
      <p class="item-meta">{{ paper.venue }} · {{ paper.year }}</p>
      <h3><a href="{{ paper.url }}">{{ paper.title }}</a></h3>
      <p>{{ paper.summary }}</p>
    </article>
    {% endfor %}
  </div>
</section>
{% endfor %}

</div>
