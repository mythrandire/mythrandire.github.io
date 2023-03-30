---
layout: page
permalink: /conferences/
title: conferences
description:
years: [2022,2021,2020,2019,2016,2015,2014]
nav: false
nav_order: 1
---
 <!-- _pages/conferences.md -->
<div class="publications">

 {%- for y in page.years %}
   <h2 class="year">{{y}}</h2>
  {% bibliography -f conferences -q @*[year={{y}}]* %}
{% endfor %}

</div>
