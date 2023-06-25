---
layout: page
permalink: /publications/
title: Publications
description: 
years: [2023, 2022, 2021, 2020, 2019, 2018, 2017, 2016, 2015, 2014, 2013, 2012, 2011, 2010, 2009, 2008, 2007, 2006, 2005, 2004, 2003, 2002, 2001, 2000, 1999, 1998, 1997, 1996, 1995, 1994, 1993]
nav: true
# nav_order: 5
---
[Google scholar](https://scholar.google.com/citations?user=jEdhxGMAAAAJ&hl=en)
[DBLP](https://dblp.org/pid/s/CyrusShahabi.html)

#### Books
<div class="publications">

{% for y in page.years %}
  {% bibliography -f books -q @*[year={{y}}]* %}
{% endfor %}

</div>

#### Book Chapters

#### Refereed Conference Papaers

#### Refereed Journal Papers

#### Invited Talks

#### Patents

#### Other Publications
