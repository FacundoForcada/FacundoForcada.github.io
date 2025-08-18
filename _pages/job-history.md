---
layout: default
title: "Job History"
---

<link rel="stylesheet" href="/assets/css/custom.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
<div class="top-left-home">
  <a class="icon-btn" href="/" title="Home">
    <i class="fas fa-house"></i>
  </a>
</div>

## Job History

Browse my professional experience below. Use the navigation to view each position.

<ul>
  {% for job in site.jobs %}
    <li>
      <a href="{{ job.url }}">{{ job.title }} at {{ job.company }} ({{ job.start_date }} - {{ job.end_date }})</a>
    </li>
  {% endfor %}
</ul>