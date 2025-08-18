---
layout: default
title: "ASP.NET Web Developer"
company: "Biwini S.A.S."
role: "Senior ASP.NET Web Developer"
start_date: "Sep 2022"
end_date: "Apr 2024"
tech_stack: ["ASP.NET", "Angular", "Javascript", "CSS", "C#", "HTML", "SQL Server", "Azure DevOps", "VS Code", "REST APIs", "SOAP"]
soft_skills: ["Team Coaching", "Customer Support", "Problem Solving", "Functional Analysis", "Business Reporting"]
projects_clients:
  - "Agencia Gubernamental de Control - Ciudad de Buenos Aires: Backoffice online tool, Backend APIs & Integrations, Citizen online portals"
description: |
  Enhanced website performance by optimizing ASP.NET code and streamlining database queries. Developed user-friendly web applications for streamlined customer experiences and increased client satisfaction. Collaborated with cross-functional teams to design, develop, and launch innovative web solutions on time and within budget. Contributed to the development of reusable code libraries, expediting future projects and enhancing overall efficiency. Conducted thorough testing to identify bugs and ensure optimal functionality before deploying web applications into production environments.
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