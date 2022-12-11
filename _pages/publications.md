---
layout: page
permalink: /research/
title: Research
description:
years: [2022,2021,2020,2019]
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
A draft of this paper is coming soon.
