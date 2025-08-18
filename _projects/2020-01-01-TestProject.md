---
title: "Portfolio Website"
github_repo: "https://github.com/yourusername/portfolio"
start_date: "Mar 2022"
end_date: "May 2022"
description: |
  A personal website to showcase my professional experience, projects, and skills.
tech_stack: ["Jekyll", "GitHub Pages", "Bootstrap"]
---

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