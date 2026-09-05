---
layout: single
title: About
permalink: /About/
author_profile: true
---

<div class="about-content" markdown="1">

## Experience

Zachary McCaw is a machine learning scientist and biostatistician. His research focuses on making scientific discovery more reliable and interpretable through new statistical and machine-learning methods. He has co-authored 70+ scientific publications, is a co-inventor on three granted U.S. patents, and has developed multiple statistical methods and open-source R packages.

<ul class="about-experience">
{% for position in site.data.experience %}
  <li><strong>{{ position.organization }}, {{ position.dates }} — {{ position.role }}:</strong> {{ position.summary }}</li>
{% endfor %}
</ul>

## Education

- **Stanford University, 2021–2022:** Graduate Certificate in Artificial Intelligence.
- **Broad Institute, 2019:** Visiting Scientist with Professor [Hilary Finucane](https://www.finucanelab.org/).
- **Harvard University, 2014–2019:** Ph.D. and A.M. in Biostatistics under Professor [Xihong Lin](https://hsph.harvard.edu/profile/xihong-lin/).
- **National Institute of Environmental Health Sciences, 2010–2014:** Research Fellow with Professor Steven Kleeberger.
- **UNC–Chapel Hill, 2009–2013:** B.S.P.H. in Biostatistics and B.S. in Quantitative Biology.

</div>
