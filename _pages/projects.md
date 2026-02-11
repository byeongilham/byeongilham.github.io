---
layout: page
permalink: /projects/
title: projects
description: Ongoing Projects
nav: true
nav_order: 3
horizontal: false
---

<div class="projects">

{% comment %} 모든 프로젝트를 중요도(importance) 순으로 정렬합니다 {% endcomment %}
{% assign sorted_projects = site.projects | sort: "importance" %}

  {% if page.horizontal %}
  <div class="container">
    <div class="row row-cols-1 row-cols-md-2">
    {% for project in sorted_projects %}
      {% include projects_horizontal.liquid %}
    {% endfor %}
    </div>
  </div>
{% else %}
  <div class="row row-cols-1 row-cols-md-3">
    {% for project in sorted_projects %}
      {% include projects.liquid %}
    {% endfor %}
  </div>
{% endif %}

</div>