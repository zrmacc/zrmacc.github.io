---
layout: single
title: Mathematics
permalink: /Collections/Mathematics/
sidebar:
  nav: "navi"
---

{% assign notes = site.mathematics | sort: "title" %}
{% include note-list.html notes=notes %}
