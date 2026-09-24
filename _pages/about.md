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
    <p class="q-lede">I am an incoming Postdoctoral Researcher at the <a href="https://www.linkedin.com/company/oxford-social-media-observatory/posts/?feedView=all" target="_blank" rel="noopener">Oxford Social Media Observatory (OSMO)</a> at the University of Oxford. My research examines how online platforms govern speech—and how users perceive, interpret, and respond to content moderation decisions and mechanisms within broader and evolving patterns of social media use.</p>

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
  <p>I recently submitted my doctoral dissertation at the Technical University of Munich (TUM), where I worked as a research associate at the <a href="https://www.hfp.tum.de/en/digitalgovernance/home/" target="_blank" rel="noopener">Chair of Digital Governance</a>. My work was situated within the project <a href="https://www.tum.de/en/news-and-events/all-news/press-releases/details/analyse-des-verhaltens-von-social-media-plattformen" target="_blank" rel="noopener"><em>Transparency in Content Moderation</em></a>, which examines how moderation rules are designed, communicated, and understood in practice, and how these processes shape user behavior and trust in platform governance.</p>
  <p>I am also involved as a research collaborator in the <a href="https://tumthinktank.de/project/content-moderation-lab/" target="_blank" rel="noopener">Content Moderation Lab</a>, incubated at the TUM Think Tank. Across projects, my research combines survey experiments, observational data, and causal inference approaches, complemented by computational analyses.</p>
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
      <h4><a href="https://osf.io/s3kcw" target="_blank" rel="noopener">Content Warning: Public Attitudes on Content Moderation and Freedom of Expression</a></h4>
      <p>Theocharis, Kosmidis, Zilinsky, Quint &amp; Pradel (2025). Covered across national and international press.</p>
      <div class="q-tags">
        <a href="https://www.sueddeutsche.de/bayern/gewalt-im-internet-umfrage-mehrheit-wuenscht-sich-kontrolle-in-sozialen-medien-dpa.urn-newsml-dpa-com-20090101-250211-930-371237" target="_blank" rel="noopener">Süddeutsche Zeitung</a><a href="https://www.instagram.com/p/DF73bbAsIWz/?hl=en" target="_blank" rel="noopener">ZDFheute</a><a href="https://www.lavanguardia.com/sociedad/20250216/10391036/79-poblacion-mundial-apoya-eliminar-mensajes-inciten-violencia-redes-sociales-agenciaslv20250216.html" target="_blank" rel="noopener">La Vanguardia</a><a href="https://www.sn.at/panorama/medien/umfrage-mehrheit-wuenscht-sich-kontrolle-in-sozialen-medien-art-580120" target="_blank" rel="noopener">Salzburger Nachrichten</a><a href="https://www.ox.ac.uk/news/2025-02-12-majority-support-moderation-social-media-platforms-global-survey-shows" target="_blank" rel="noopener">University of Oxford</a><a href="https://www.tum.de/en/news-and-events/all-news/press-releases/details/majority-support-moderation-on-social-media-platforms" target="_blank" rel="noopener">TUM</a>
      </div>
    </div>
    <div class="q-card">
      <div class="q-kicker q-kicker--accent">Writing &amp; interviews</div>
      <h4><a href="https://www.techpolicy.press/what-people-want-from-platforms-isnt-what-musk-and-zuckerberg-are-selling/" target="_blank" rel="noopener">What People Want from Platforms Isn't What Musk and Zuckerberg Are Selling</a></h4>
      <p>Tech Policy Press, May 2025. Plus an interview on moderation demand for ver.di, Menschen machen Medien.</p>
      <div class="q-tags">
        <a href="https://www.techpolicy.press/what-people-want-from-platforms-isnt-what-musk-and-zuckerberg-are-selling/" target="_blank" rel="noopener">Tech Policy Press</a><a href="https://mmm.verdi.de/aktuelle-meldungen/soziale-medien-mehr-moderation-gewuenscht-101943/" target="_blank" rel="noopener">ver.di – Menschen machen Medien</a>
      </div>
    </div>
  </div>
</section>

<section class="q-section">
  <div class="q-shead">
    <h2>Off the clock</h2>
    <div class="q-kicker">Books</div>
  </div>

  <div class="q-reading">
    <div class="q-kicker">Currently reading</div>
    <div class="q-books">
      {%- for b in site.data.reading.current %}
      <div class="q-book">
        <span class="q-book-edge" style="background:{{ b.color | default: '#5B7A61' }}"></span>
        <span class="q-book-body">
          <span class="q-book-t">{{ b.title }}</span>
          <span class="q-book-a">{{ b.author }}</span>
        </span>
      </div>
      {%- endfor %}
    </div>

    {%- if site.data.reading.best and site.data.reading.best.size > 0 %}
    <div class="q-best">
      <div class="q-kicker">Best of {{ site.data.reading.year }} so far</div>
      {%- for b in site.data.reading.best %}
      <div class="q-best-row">
        <span class="q-best-no">{{ forloop.index }}</span>
        <span class="q-best-t">{{ b.title }}<small>{{ b.author }}</small></span>
      </div>
      {%- endfor %}
    </div>
    {%- endif %}
  </div>
</section>
