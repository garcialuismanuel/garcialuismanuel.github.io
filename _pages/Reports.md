---
layout: page
title: Reports
permalink: /Reports/
description: Notebooks/Rmd files that showcase my machine learning and data analysis skills. The "Reports" page has the business-oriented presentation of findings while this page leans more into the technical aspects. This includes the cleaning and transforming of data,  EDA, and model selection process. 
nav: true
nav_order: 2
display_categories: [R-Projects, Python-Projects, Misc/Archive]
horizontal: false
---

<!-- pages/Reports.md -->
<div class="Reports">
{%- if site.enable_Reports_categories and page.display_categories %}
  <!-- Display categorized Reports -->
  {%- for category in page.display_categories %}
  <h2 class="category">{{ category }}</h2>
  {%- assign categorized_Reports = site.Reports | where: "category", category -%}
  {%- assign sorted_Reports = categorized_Reports | sort: "importance" %}
  <!-- Generate cards for each Reports -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for Reports in sorted_Reports -%}
      {% include Reports_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for Reports in sorted_Reports -%}
      {% include Reports.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
  {% endfor %}

{%- else -%}
<!-- Display Reports without categories -->
  {%- assign sorted_Reports = site.Reports | sort: "importance" -%}
  <!-- Generate cards for each Reports -->
  {% if page.horizontal -%}
  <div class="container">
    <div class="row row-cols-2">
    {%- for Reports in sorted_Reports -%}
      {% include Reports_horizontal.html %}
    {%- endfor %}
    </div>
  </div>
  {%- else -%}
  <div class="grid">
    {%- for Reports in sorted_Reports -%}
      {% include Reports.html %}
    {%- endfor %}
  </div>
  {%- endif -%}
{%- endif -%}
</div>
