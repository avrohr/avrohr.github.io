---
layout: page
permalink: /publications/
title: publications
description: 
years: [2022, 2021, 2020, 2018]
nav: true
nav_order: 1
---

\* denotes equal contribution.
You can also find my articles on [Google Scholar](https://scholar.google.de/citations?user=hB2Q6DUAAAAJ).

<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
