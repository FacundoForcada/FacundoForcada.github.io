---
layout: default
title: "Certificates"
---

<link rel="stylesheet" href="/assets/css/custom.css">
<link rel="stylesheet" href="https://cdnjs.cloudflare.com/ajax/libs/font-awesome/6.4.2/css/all.min.css">
<div class="top-left-home">
  <a class="icon-btn" href="/" title="Home">
    <i class="fas fa-house"></i>
  </a>
</div>

## Certificates

Browse my professional certificates below.

<ul>
  {% for certificate in site.certificates %}
    <li>
      <a href="{{ certificate.url }}">{{ certificate.title }} - {{ certificate.platform }} ({{ certificate.start_date }} - {{ certificate.end_date }})</a>
    </li>
  {% endfor %}
</ul>