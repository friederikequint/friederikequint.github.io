---
layout: quint
nav_key: about
title: "About"
permalink: /
description: "I study how online platforms govern speech and how users perceive, interpret and respond to content moderation."
---

<div class="q-hero">
  <div class="q-portrait">
    <div class="q-portrait-outline"></div>
    <div class="q-portrait-img">
      <img src="{{ '/images/portrait-new.jpg' | relative_url }}" alt="Friederike Quint">
    </div>
  </div>
  <div>
    <p class="q-lede">I am a doctoral researcher studying how online platforms govern speech—and how users perceive, interpret, and respond to content moderation decisions and mechanisms within broader and evolving patterns of social media use.</p>

    <div class="q-chips">
      <span>Content moderation</span>
      <span>Platform governance</span>
      <span>Political communication</span>
      <span>Online participation &amp; disengagement</span>
      <span>Survey experiments</span>
      <span>Computational social science</span>
    </div>

    <div class="q-now">
      <div class="q-now-row">
        <div class="q-now-label">New paper</div>
        <div class="q-now-title">Does the Community Understand the Community Guidelines?</div>
        <div class="q-now-meta q-now-meta--accent">Policy &amp; Internet</div>
      </div>
      <div class="q-now-row">
        <div class="q-now-label">Next talk</div>
        <div class="q-now-title">Digital Publics Conference, University of Zurich</div>
        <div class="q-now-meta">Zurich, Oct 2026</div>
      </div>
    </div>
  </div>
</div>

<div class="q-prose">
  <p>I have recently submitted my dissertation and have been a research associate at the Chair of Digital Governance at the Technical University of Munich, where my work sits within the project <em>Transparency in Content Moderation</em>, which asks how moderation rules are designed, communicated, and understood in practice, and how these processes shape user behavior and trust in platform governance.</p>
  <p>Further, I am involved as a research collaborator in the Content Moderation Lab, incubated at the TUM Think Tank. Across projects, my research combines survey experiments, observational data, and causal inference approaches, complemented by computational analyses.</p>
  <p class="q-tease">The next chapter starts in November. More on that here soon.</p>
</div>

<section class="q-section">
  <div class="q-shead">
    <h2>Published work</h2>
    <a class="q-kicker q-kicker--accent" href="{{ '/publications/' | relative_url }}">All research →</a>
  </div>
  <div class="q-shelf">
    {%- for p in site.data.publications.peer_reviewed %}{% if p.featured %}
    <a class="q-shelf-card" href="{{ p.doi }}" target="_blank" rel="noopener">
      <div class="q-cover">
        <div class="q-cover-spine"></div>
        <div class="q-cover-img"><img src="{{ p.cover | relative_url }}" alt="{{ p.cover_alt }}"></div>
      </div>
      <div class="q-shelf-meta"><b>{{ p.short_title | default: p.title }}</b>{{ p.short_authors }}</div>
      <div class="q-shelf-foot"><span>{{ p.short_venue }}</span><b>→</b></div>
    </a>
    {%- endif %}{% endfor %}
  </div>
</section>

<section class="q-section">
  <div class="q-shead">
    <h2>In the public conversation</h2>
    <div class="q-kicker">Media &amp; policy</div>
  </div>
  <div class="q-cards-2">
    <div class="q-card">
      <div class="q-kicker q-kicker--accent">Research report</div>
      <h4>Content Warning: Public Attitudes on Content Moderation and Freedom of Expression</h4>
      <p>Theocharis, Kosmidis, Zilinsky, Quint &amp; Pradel (2025). Covered across national and international press.</p>
      <div class="q-tags">
        <i>Süddeutsche Zeitung</i><i>ZDFheute</i><i>La Vanguardia</i><i>Handelszeitung</i><i>Salzburger Nachrichten</i>
      </div>
    </div>
    <div class="q-card">
      <div class="q-kicker q-kicker--accent">Writing &amp; interviews</div>
      <h4>What People Want from Platforms Isn't What Musk and Zuckerberg Are Selling</h4>
      <p>Tech Policy Press, May 2025. Plus an interview on moderation demand for ver.di, Menschen machen Medien.</p>
      <div class="q-tags">
        <i>Tech Policy Press</i><i>ver.di</i><i>University of Oxford</i><i>TUM</i>
      </div>
    </div>
  </div>
</section>
