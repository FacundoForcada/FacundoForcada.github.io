---
layout: default
title: "Technical Lead Software Engineer"
company: "Biwini S.A.S."
role: "Technical Lead Software Engineer"
start_date: "Feb 2023"
end_date: "Apr 2024"
tech_stack: ["ASP.NET", "Angular", "Javascript", "CSS", "C#", "HTML", "SQL Server", "Azure DevOps", "VS Code", "REST APIs", "SOAP", "React", "Oracle Databases", "PostgreSQL"]
soft_skills: ["Leadership", "Team management", "Project Management", "Customer Support", "Problem Solving", "Functional Analysis", "Business Reporting"]
projects_clients:
  - "Agencia Gubernamental de Control - Ciudad de Buenos Aires: Backoffice online tool, Backend APIs & Integrations, Citizen online portals"
description: |
  Optimized resource allocation for improved team productivity and timely project completion. Improved client satisfaction with consistent status updates and prompt resolutions to concerns. Managed cross-functional teams to deliver high-quality software products within deadline constraints. Developed comprehensive project plans, ensuring clear communication of goals and expectations to all stakeholders. Mentored junior staff members, fostering professional growth through knowledge sharing and skill development opportunities. Facilitated stakeholder collaboration through regular meetings, progress reports, and open lines of communication throughout the project life cycle.
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