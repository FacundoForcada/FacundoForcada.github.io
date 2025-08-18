---
layout: default
title: "Technical Lead Software Engineer"
company: "Capgemini ER&D Argentina"
role: "Technical Lead Software Engineer"
start_date: "Apr 2024"
end_date: "Present"
tech_stack: ["C#", "Angular", "Javascript", "Typescript", "SQL Server", "IBM AS 400", "Azure DevOps", "Terraform", "Azure Infrastructure", "Azure Cloud Services"]
soft_skills: ["Leadership", "Mentoring", "Agile", "Coaching", "Business Analysis", "Problem Solving"]
projects_clients:
  - "First Command Financial Services: Advisors Services and Platforms"
description: |
  Led a team of developers to build scalable web applications for First Command Financial Services. Responsible for architecture, code reviews, and mentoring.
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