---
layout: page
title: Courses
permalink: /courses/
nav: false
---

<!-- pages/courses.md -->
<div class="projects">
<!-- Display courses without categories -->
  {%- assign sorted_courses = site.course | sort: "importance" -%}
  <!-- Generate cards for each project -->
  <!-- {% if page.horizontal -%} -->
  <div class="container">
    <div class="row row-cols-2">
    {%- for course in sorted_courses -%}
      {% include courses.html %}
    {%- endfor %}
    </div>
  </div>
  <!-- {%- else -%}
  <div class="grid">
    {%- for project in sorted_projects -%}
      {% include projects.html %}
    {%- endfor %}
  </div>
  {%- endif -%} -->
<!-- {%- endif -%} -->
</div>