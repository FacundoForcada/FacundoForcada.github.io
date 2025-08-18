---
layout: default
title: "Desktop Software Developer"
company: "Recursos Informaticos S.R.L."
role: "From Junior to Senior Software Developer"
start_date: "Aug 2017"
end_date: "Dec 2020"
tech_stack: ["Oracle PL/SQL", "OpenText Gupta SQL Base", "C#", "ASP.NET", "VB.NET"]
soft_skills: ["Coaching", "Ethics", "Agile", "Pair-Programming", "Problem Solving"]
projects_clients:
  - "Refineria del Centro: CRM Tool, Administrative Tool, HR Tool & Storage Management Tool"
  - "Paclin: CRM Tool, Administrative Tool & Storage Management Tool"
  - "Pellacani: CRM Tool, Administrative Tool & Storage Management Tool"
description: |
  Improved software efficiency by troubleshooting and resolving coding issues. Collaborated with cross-functional teams to deliver high-quality products on tight deadlines. Optimized application performance by conducting regular code reviews and refactoring when necessary. Increased development speed by automating repetitive tasks using scripts and tools. Contributed to a positive team environment through effective communication, problem-solving, and collaboration skills.
---

<link rel="stylesheet" href="/assets/css/custom.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
<div class="top-left-home">
  <a class="icon-btn" href="/job-history/" title="Home">
    <i class="fas fa-briefcase"></i>
  </a>
</div>

### {{ page.title }} at {{ page.company }}

**Role:** {{ page.role }}  
**Period:** {{ page.start_date }} - {{ page.end_date }}

#### Description
{{ page.description }}

#### Technology Stack
<ul>
  {% for tech in page.tech_stack %}
    <li>{{ tech }}</li>
  {% endfor %}
</ul>

#### Key Soft Skills
<ul>
  {% for skill in page.soft_skills %}
    <li>{{ skill }}</li>
  {% endfor %}
</ul>

#### Projects / Clients
<ul>
  {% for project in page.projects_clients %}
    <li>{{ project }}</li>
  {% endfor %}
</ul>