---
layout: default
title: "Technical Lead Software Engineer"
company: "Recursos Informaticos S.R.L."
role: "Technical Lead Software Engineer"
start_date: "Jan 2021"
end_date: "Aug 2022"
tech_stack: ["Oracle PL/SQL", "OpenText Gupta SQL Base", "C#", "ASP.NET", "VB.NET", "Javascript", "SQL Server", "Rest APIs"]
soft_skills: ["Leadership", "Ethics", "Agile", "Onboarding", "Business Analysis", "Technical Interview", "Customer Support"]
projects_clients:
  - "Refineria del Centro: CRM Tool, Administrative Tool, HR Tool & Storage Management Tool"
  - "Paclin: CRM Tool, Administrative Tool & Storage Management Tool"
  - "Pellacani: CRM Tool, Administrative Tool & Storage Management Tool"
description: |
  Collaborated with cross-functional teams to develop high-quality software products within tight deadlines. Mentored junior developers, improving their coding skills and fostering a positive team environment. Streamlined development processes by introducing agile methodologies, resulting in faster project completion times. Delivered exceptional customer support, effectively resolving complex technical issues and ensuring client satisfaction. Contributed to the successful completion of multiple projects by providing strong leadership and expert technical guidance. Conducted regular training sessions for team members on new technologies and programming techniques, enhancing overall team competence levels.
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