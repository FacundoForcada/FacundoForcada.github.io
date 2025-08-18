---
layout: default
title: "Liderazgo Orientado al Florecimiento Humano"
platform: "Coursera"
certificate_link: "https://www.coursera.org/account/accomplishments/records/NQB2PO5P6SN7"
start_date: "Jul 2025"
end_date: "Jul 2025"
grade: "Passed - 99.25%"
description: |
  This leadership course will provide the necessary tools to develop leadership skills geared toward personal and professional development, providing the skills needed by the modern leader. Organizational leadership and the motivation that leaders generate in their employees are fundamental to the success of organizations. This online course provides the tools for leaders to develop professionally within an organization, positively impacting organizational behavior.
topics:
  - "Leadership in a new era"
  - "Awareness of oneself and one's surroundings"
  - "Positivity and Resilience"
  - "Meaning and Commitment"
---

<link rel="stylesheet" href="/assets/css/custom.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
<div class="top-left-home">
  <a class="icon-btn" href="/certificates/" title="Home">
    <i class="fas fa-certificate"></i>
  </a>
</div>

### {{ page.title }}

**Platform:** {{ page.platform }}  
**Certificate:** [View Certificate]({{ page.certificate_link }})  
**Period:** {{ page.start_date }} - {{ page.end_date }}  
**Grade:** {{ page.grade }}

#### Description
{{ page.description }}

#### Topics Learned
<ul>
  {% for topic in page.topics %}
    <li>{{ topic }}</li>
  {% endfor %}
</ul>