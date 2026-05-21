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
- [국문 Academic CV PDF]({{ "/files/Kang_Yongguk_CV_KO.pdf" | relative_url }})
- [국문 Industry Resume PDF]({{ "/files/Kang_Yongguk_Resume_KO.pdf" | relative_url }})

## Current Position

Research Professor, Imaging Intelligence Laboratory, School of Mechanical Engineering, Seoul National University.

## Publications

<ul>
{% assign sorted_publications = site.publications | sort: "date" | reverse %}
{% for post in sorted_publications %}
  {% include archive-single-cv.html %}
{% endfor %}
</ul>
