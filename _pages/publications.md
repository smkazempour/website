---
layout: page
permalink: /research/
title: Research
description:
years: [2022,2021]
nav: true
nav_order: 2
---
<!-- _pages/publications.md -->
<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>

### Works in Progress:
---
**Are Twitter Users Informed about Stocks?**, with Ali Kakhbod and Peiyao Li
**Heterogeneity in Twitter: A Topic Modeling Approach**, with Ali Kakhbod
**Government Subsidies and Industry Concentration**, with Gustavo Grullon and Yessenia Tellez
