---
layout: quint
nav_key: cv
title: "CV"
permalink: /cv/
description: "Education, appointments, training and references. The full record is in the PDF."
redirect_from:
  - /resume
---

<div class="q-pagehead">
  <div class="q-kicker">Curriculum vitae</div>
  <h1>Education, appointments, training, and references. The full record is in the PDF.</h1>
</div>

<div class="q-cta">
  <a class="q-btn-lg" href="{{ '/cv/Friederike-Quint-CV.pdf' | relative_url }}" download="Friederike-Quint-CV.pdf">Download CV (PDF) <span aria-hidden="true">↓</span></a>
  <a class="q-btn-lg-ghost" href="mailto:{{ site.author.email }}">{{ site.author.email }}</a>
  <span class="q-updated">Last updated {{ site.data.cv.updated }}</span>
</div>

<section class="q-section">
  <div class="q-shead"><h2>Research interests</h2></div>
  <div class="q-pillrow">
    {%- for i in site.data.cv.interests %}
    <span>{{ i }}</span>
    {%- endfor %}
  </div>
</section>

<section class="q-section">
  <div class="q-shead"><h2>Education</h2></div>
  {%- for e in site.data.cv.education %}
  <div class="q-entry">
    <div class="q-entry-date">{{ e.date }}</div>
    <div>
      <h4>{{ e.title }}</h4>
      <div class="q-entry-meta">{{ e.meta }}</div>
    </div>
  </div>
  {%- endfor %}
</section>

<section class="q-section">
  <div class="q-shead"><h2>Professional experience</h2></div>
  {%- for e in site.data.cv.experience %}
  <div class="q-entry">
    <div class="q-entry-date">{{ e.date }}</div>
    <div>
      <h4>{{ e.title }}</h4>
      <div class="q-entry-meta">{{ e.meta }}</div>
    </div>
  </div>
  {%- endfor %}
</section>

<section class="q-section">
  <div class="q-shead"><h2>Additional training</h2></div>
  {%- for e in site.data.cv.training %}
  <div class="q-entry">
    <div class="q-entry-date">{{ e.date }}</div>
    <div>
      <h4>{{ e.title }}</h4>
      <div class="q-entry-meta">{{ e.meta }}</div>
    </div>
  </div>
  {%- endfor %}
</section>

<section class="q-section">
  <div class="q-shead"><h2>Languages &amp; skills</h2></div>
  <div class="q-grid-3">
    {%- for s in site.data.cv.skills %}
    <div>
      <div class="q-sublabel">{{ s.label }}</div>
      <p>{{ s.body }}</p>
    </div>
    {%- endfor %}
  </div>
</section>

<section class="q-section">
  <div class="q-shead"><h2>Academic references</h2></div>
  <div class="q-cards-2">
    {%- for r in site.data.cv.references %}
    <div class="q-ref">
      <h4>{{ r.name }}</h4>
      <p>{{ r.affiliation }}</p>
      <a href="mailto:{{ r.email }}">{{ r.email }}</a>
    </div>
    {%- endfor %}
  </div>
</section>
