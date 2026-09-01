---
layout: quint
nav_key: research
title: "Research"
permalink: /publications/
description: "Peer-reviewed articles, research reports and work in progress on platform governance, content moderation and political communication."
---

<div class="q-pagehead">
  <div class="q-kicker">Research</div>
  <h1>Platforms govern speech. People take part, push back, or go quiet.</h1>
</div>

<section class="q-section">
  <div class="q-shead"><h2>Peer-reviewed articles</h2></div>

  {%- for p in site.data.publications.peer_reviewed %}
  <div class="q-paper{% if forloop.first %} q-paper--first{% endif %}">
    {%- if p.cover %}
    <a class="q-thumb" href="{{ p.doi }}" target="_blank" rel="noopener" title="Open the paper">
      <span class="q-thumb-spine"></span>
      <span class="q-thumb-img"><img src="{{ p.cover | relative_url }}" alt="{{ p.cover_alt }}"></span>
    </a>
    {%- else %}<div></div>{% endif %}
    <div>
      <h3>{{ p.title }}</h3>
      <div class="q-authors">{{ p.authors }}</div>
      <div class="q-venue">{{ p.venue }}</div>
      {%- if p.note %}<div class="q-note">{{ p.note }}</div>{% endif %}
      <div class="q-links">
        <a class="q-primary" href="{{ p.doi }}" target="_blank" rel="noopener">{{ p.link_label | default: "DOI →" }}</a>
        {%- if p.pdf %}<a href="{{ p.pdf | relative_url }}" target="_blank">PDF</a>{% endif %}
        {%- if p.replication %}<a href="{{ p.replication }}" target="_blank" rel="noopener">Replication data</a>{% endif %}
      </div>
    </div>
    <div class="q-year">{{ p.year }}</div>
  </div>
  {%- endfor %}
</section>

<section class="q-section">
  <div class="q-shead"><h2>Research report</h2></div>

  {%- for p in site.data.publications.reports %}
  <div class="q-paper q-paper--first">
    {%- if p.cover %}
    <a class="q-thumb" href="{{ p.doi }}" target="_blank" rel="noopener" title="Open the report">
      <span class="q-thumb-spine"></span>
      <span class="q-thumb-img"><img src="{{ p.cover | relative_url }}" alt="{{ p.cover_alt }}"></span>
    </a>
    {%- else %}<div></div>{% endif %}
    <div>
      <h3>{{ p.title }}</h3>
      <div class="q-authors">{{ p.authors }}</div>
      <div class="q-venue">{{ p.venue }}</div>
      {%- if p.note %}<div class="q-note">{{ p.note }}</div>{% endif %}
      <div class="q-links">
        <a class="q-primary" href="{{ p.doi }}" target="_blank" rel="noopener">{{ p.link_label | default: "DOI →" }}</a>
        {%- if p.pdf %}<a href="{{ p.pdf | relative_url }}" target="_blank">PDF</a>{% endif %}
        {%- if p.replication %}<a href="{{ p.replication }}" target="_blank" rel="noopener">Replication data</a>{% endif %}
      </div>
    </div>
    <div class="q-year">{{ p.year }}</div>
  </div>
  {%- endfor %}
</section>

<section class="q-section">
  <div class="q-shead q-shead--tight"><h2>Work in progress</h2></div>
  <div class="q-wip">
    {%- for w in site.data.work_in_progress %}
    <div class="q-wip-row">
      <div>
        <h4>{{ w.title }}</h4>
        <div class="q-wip-authors">{{ w.authors }}</div>
      </div>
      <div class="q-status">{{ w.status }}</div>
    </div>
    {%- endfor %}
  </div>
</section>
