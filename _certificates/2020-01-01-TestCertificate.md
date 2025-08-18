---
title: "AWS Certified Solutions Architect"
platform: "AWS"
certificate_link: "https://www.yourcertificateurl.com"
start_date: "May 2021"
end_date: "May 2024"
grade: "Pass"
description: |
  This certification validates expertise in designing and deploying scalable systems on AWS.
topics:
  - "AWS Compute"
  - "Networking"
  - "Storage"
  - "Security"
  - "Best Practices"
---

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