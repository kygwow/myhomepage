---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

## Downloads

- [Academic CV PDF]({{ "/files/Kang_Yongguk_CV.pdf" | relative_url }})
- [Industry Resume PDF]({{ "/files/Kang_Yongguk_Resume.pdf" | relative_url }})

## Current Position

Research Professor, Imaging Intelligence Laboratory, School of Mechanical Engineering, Seoul National University.

## Publications

<ul>
{% for post in site.publications reversed %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
