---
layout: default
title: "Personal Projects"
---

<link rel="stylesheet" href="/assets/css/custom.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
<div class="top-left-home">
  <a class="icon-btn" href="/" title="Home">
    <i class="fas fa-house"></i>
  </a>
</div>

## Personal Projects

Explore some of my key personal projects below.

<ul>
  {% for project in site.projects %}
    <li>
      <a href="{{ project.url }}">{{ project.title }} ({{ project.start_date }} - {{ project.end_date }})</a>
    </li>
  {% endfor %}
</ul>