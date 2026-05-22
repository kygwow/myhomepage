---
permalink: /
title: "Yong Guk Kang"
author_profile: true
redirect_from:
  - /about/
  - /about.html
---

<section class="home-hero">
  <p class="home-kicker">Computational imaging / Optical systems / Biomedical photonics</p>
  <h1>Yong Guk Kang</h1>
  <p class="home-lead">Research Professor in the Imaging Intelligence Laboratory at Seoul National University, working with Prof. Seung Ah Lee.</p>
  <p>I develop computational imaging methods that connect optical system modeling, inverse optical design, wave-optics simulation, and data-driven reconstruction. My current work focuses on lensless and phase-coded imaging systems, quantitative phase imaging, and AI-assisted image reconstruction for optical and biomedical applications.</p>
  <div class="home-actions">
    <a class="home-button" href="{{ "/files/Kang_Yongguk_CV.pdf" | relative_url }}">Academic CV</a>
    <a class="home-link" href="mailto:ygkang@snu.ac.kr">ygkang@snu.ac.kr</a>
  </div>
</section>

<section class="home-section">
  <h2>Research Areas</h2>
  <div class="home-area-list">
    <div class="home-area">
      <h3>Computational Imaging and Inverse Optical Design</h3>
      <p>Physics-informed modeling, differentiable simulation, and optimization of optical encoding and image reconstruction pipelines.</p>
    </div>
    <div class="home-area">
      <h3>Lensless and Phase-Coded Imaging</h3>
      <p>Sampling-efficient wave propagation, phase-coded measurements, and reconstruction strategies for compact computational imaging systems.</p>
    </div>
    <div class="home-area">
      <h3>Quantitative Phase and Coherent Microscopy</h3>
      <p>Interferometric and coherent imaging methods for quantitative optical measurements in biomedical and surface inspection contexts.</p>
    </div>
  </div>
</section>

<section class="home-section">
  <h2>Selected Publications</h2>
  <div class="home-publications">
    {% assign sorted_publications = site.publications | sort: "date" | reverse %}
    {% for post in sorted_publications limit: 5 %}
      <article class="home-publication">
        <a href="{{ post.url | relative_url }}">{{ post.title }}</a>
        <span>{{ post.venue }} / {{ post.date | date: "%Y" }}</span>
      </article>
    {% endfor %}
  </div>
  <p class="home-small"><a href="{{ "/publications/" | relative_url }}">Full publication list</a></p>
</section>

<section class="home-section">
  <h2>Links</h2>
  <p class="home-link-row">
    <a href="https://scholar.google.com/citations?hl=ko&authuser=1&user=YH1e9WMAAAAJ">Google Scholar</a>
    <a href="https://orcid.org/0000-0002-5572-7544">ORCID</a>
    <a href="https://github.com/kygwow">GitHub</a>
  </p>
</section>
