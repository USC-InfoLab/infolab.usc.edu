---
layout: page
permalink: /invited_talks/
title: Invited Talks
description: 
years: [2023, 2022, 2021, 2020, 2019, 2018, 2016, 2015, 2014, 2013, 2012, 2011, 2010, 2009, 2008, 2007, 2006, 2005, 2004, 2003]
nav: false
---

<div class="publications">

{%- for y in page.years %}
  <h2 class="year">{{y}}</h2>
  {% bibliography -f talks -q @*[year={{y}}]* %}
{% endfor %}