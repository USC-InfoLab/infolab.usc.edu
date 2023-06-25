---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012, 2011, 2010]
nav: true
# nav_order: 5
---
[[Google scholar](https://scholar.google.com/citations?user=jEdhxGMAAAAJ&hl=en)] | [[DBLP](https://dblp.org/pid/s/CyrusShahabi.html)]

#### Books

<div class="publications">

{% for y in page.years %}
  {% bibliography -f books -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Book Chapters

<div class="publications">

{% for y in page.years %}
  {% bibliography -f booksc -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Refereed Conference Papaers

<div class="publications">

{% for y in page.years %}
  {% bibliography -f conf -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Refereed Journal Papers

<div class="publications">

{% for y in page.years %}
  {% bibliography -f journal -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Invited Talks

<div class="publications">

{% for y in page.years %}
  {% bibliography -f talk -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Patents

<div class="publications">

{% for y in page.years %}
  {% bibliography -f patent -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Other Publications

<div class="publications">

{% for y in page.years %}
  <div>{{y}}</div>
  {% bibliography -f pubs -q @*[year={{y}}]* %}
{% endfor %}

</div>
