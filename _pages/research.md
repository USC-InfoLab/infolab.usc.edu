---
layout: page
title: Research
permalink: /research/
description: 
nav: true
nav_order: 3
display_categories: [current, previous]
horizontal: false
---

<!-- pages/projects.md -->
<div class="projects">
{%- if site.enable_project_categories and page.display_categories %}
  <!-- Display categorized projects -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_projects = site.projects | where: "category", category -%}
  {%- assign sorted_projects = categorized_projects | sort: "importance" %}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display projects without categories -->
  {%- assign sorted_projects = site.projects | sort: "importance" -%}
  <!-- Generate cards for each project -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for project in sorted_projects -%}
      {% include projects_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>

### Past Research
- Traffic Prediction
- Human Performance Optimization
- Outlier detection in data streams
- Scenic trip planning on road networks
- Mobile Video Data Management
- Spatial Crowdsourcing
- GeoSocial Networks
- WOLAP: Wavelet-based Online Analytical Processing
- Privacy in Location-Based Services
- Visibility Computation for Trajectories
- Image Acquisition Planning
- K-Nearest Neighbor Queries Over Moving Objects on Road Networks
- Surface KNN Queries
- Database Outsourcing
- Private Participatory Urban Sensing
- Road Network Traffic Modeling
- Location-based Web Search
- Subspace Method
- Texture Generation
- Nearest Neighbor Search
- Geospatial Data Fusion
- Spatial Data Stream
- Temporal Abstraction of Immersive Data Stream
- Multivariate Time Series Analysis
- Peer-to-Peer Search
- Web Services Discovery
- Query Customization
- Continous Media Servers
- Shape Retrieval