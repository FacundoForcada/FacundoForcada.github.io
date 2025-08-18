---
layout: default
title: "Liderazgo y comportamiento organizacional"
platform: "Coursera"
certificate_link: "https://www.coursera.org/account/accomplishments/verify/0DP02T8BORK5"
start_date: "Jun 2025"
end_date: "Jul 2025"
grade: "Passed - 90.25%"
description: |
  In this leadership course, you'll learn the fundamentals of workplace psychology so you can better understand others and guide them toward shared goals.
topics:
  - "Why do you want to be a leader?"
  - "What kind of leader can you be?"
  - "How can you persuade and influence people?"
  - "How can you motivate and inspire people?"
  - "Are you a formal or informal leader?"
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