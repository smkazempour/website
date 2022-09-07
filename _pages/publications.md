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
### Papers
---


<div class="publications">
{%- for y in page.years %}
  {% bibliography -f papers -q @*[year={{y}}]* %}
{% endfor %}

</div>
  

### Works in Progress:
---


- **Are Twitter Users Informed about Stocks?**, with Ali Kakhbod.
- **Beyond Sentiment: Predicting Returns Using Twitter Content**, with Ali Kakhbod and Peiyao Li.
- **Unintended Consequences of Government Contracts**, with Gustavo Grullon and Yessenia Tellez.
