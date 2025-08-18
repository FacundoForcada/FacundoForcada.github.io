---
layout: default
title: "Portfolio Website"
github_repo: "https://github.com/yourusername/portfolio"
start_date: "Jul 2025"
end_date: "Aug 2025"
description: |
  A personal website to showcase my professional experience, projects, and skills.
tech_stack: ["Jekyll", "GitHub Pages", "Bootstrap"]
---

<link rel="stylesheet" href="/assets/css/custom.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
<div class="top-left-home">
  <a class="icon-btn" href="/personal-projects/" title="Home">
    <i class="fas fa-diagram-project"></i>
  </a>
</div>

### {{ page.title }}

**GitHub Repository:** [View on GitHub]({{ page.github_repo }})  
**Period:** {{ page.start_date }} - {{ page.end_date }}

#### Description
{{ page.description }}

#### Technology Stack
<ul>
  {% for tech in page.tech_stack %}
    <li>{{ tech }}</li>
  {% endfor %}
</ul>