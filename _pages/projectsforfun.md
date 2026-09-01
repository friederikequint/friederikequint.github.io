---
layout: quint
nav_key: fun
title: "Fun Projects"
permalink: /projectsforfun/
description: "Side projects, data visualisations and small tools built outside formal research."
---

<div class="q-pagehead">
  <div class="q-kicker">Fun projects</div>
  <h1>Side projects, data visualisations, and things built out of curiosity.</h1>
</div>

<div class="q-intro">
  <p>This page hosts a small collection of exploratory side projects developed alongside my academic work. If you have questions, ideas, or would like to discuss any of these projects, feel free to reach out via <a href="mailto:{{ site.author.email }}">email</a>.</p>
  <p>These projects are driven by curiosity, experimentation, and a desire to build lightweight, usable tools outside formal research contexts.</p>
  <p class="q-disclaimer">Disclaimer: I am not a developer, but I am always keen to learn about and explore new ways of thinking, technologies, and more :)</p>
</div>

<div class="q-projects">

  <article class="q-project">
    <div>
      <div class="q-kicker q-kicker--accent">iOS · Swift</div>
      <h3>SanityApp</h3>
      <p><b>SanityApp</b> is a simple iOS mood-tracking application built with Swift. It allows users to log how they're feeling, reflect on past entries, and gain a lightweight overview of their emotional wellbeing over time.</p>
      <p>The app is intentionally designed as a clean, extendable starting point for personal use, experimentation, or further development of wellbeing-focused mobile applications.</p>
      <div class="q-project-label">What the app does</div>
      <ul>
        <li>Record daily mood entries (daily mood, stress level, optional notes)</li>
        <li>Review previously logged moods</li>
        <li>Reflect on emotional patterns over time</li>
        <li>Use a lightweight, private self-reflection tool</li>
        <li>Download your data for further analysis</li>
      </ul>
      <div class="q-tags"><i>Swift</i><i>iOS</i><i>Open source</i></div>
      <div class="q-project-actions">
        <a class="q-btn" href="https://github.com/friederikequint/SanityApp/tree/main" target="_blank" rel="noopener">View on GitHub →</a>
      </div>
      <div class="q-status-note">Status: done for now :)</div>
    </div>
    <div class="q-shot">
      <div class="q-shot-frame">
        <video controls preload="metadata" playsinline
               poster="{{ '/images/projects/sanityapp-poster.jpg' | relative_url }}">
          <source src="{{ '/assets/Updated Showcasing SanityApp.mp4' | relative_url }}" type="video/mp4">
          Your browser does not support the video tag.
        </video>
      </div>
      <div class="q-shot-cap">SanityApp demo · © Friederike Quint</div>
    </div>
  </article>

  <article class="q-project">
    <div>
      <div class="q-kicker q-kicker--accent">R · Shiny</div>
      <h3>SanityApp Shiny Edition</h3>
      <p><b>SanityApp Shiny Edition</b> (also called <em>Sanity Chronicles</em>) is a mobile-friendly Shiny application for daily mood and stress tracking, built with R and designed for private, lightweight self-reflection.</p>
      <p>The app allows users to log a single daily entry within a defined evening time window, explore their emotional states through calendar and trend views, and export their data for personal reflection or further analysis. It is intentionally built as a flexible, extendable starting point for experimenting with personal wellbeing data, Shiny-based interfaces, and lightweight self-tracking tools.</p>
      <div class="q-project-label">What the app does</div>
      <ul>
        <li>Record one mood and stress entry per day (with optional notes)</li>
        <li>Restrict entries to a defined daily time window (evening reflection)</li>
        <li>Visualize moods across a yearly calendar and trend plots</li>
        <li>Support private (owner) and public demo (guest) usage modes</li>
        <li>Export entries as CSV or JSON files</li>
        <li>Run locally or with persistent storage via a database backend</li>
      </ul>
      <div class="q-tags"><i>R</i><i>Shiny</i><i>Posit Connect Cloud</i><i>Open source</i></div>
      <div class="q-project-actions">
        <a class="q-btn" href="https://friederikequint-shinychronicles-app.share.connect.posit.cloud" target="_blank" rel="noopener">Open the Shiny app →</a>
        <a class="q-btn-ghost" href="https://github.com/friederikequint/ShinyChronicles-app" target="_blank" rel="noopener">View on GitHub →</a>
      </div>
      <div class="q-status-note">Status: happy, done for now, and still open for changes :)</div>
    </div>
    <div class="q-shot">
      <div class="q-shot-frame">
        <img src="{{ '/images/projects/shinychronicles-overview.png' | relative_url }}"
             alt="Example overview of the Sanity Chronicles Shiny app" loading="lazy">
      </div>
      <div class="q-shot-cap">Example overview from the SanityApp Shiny Edition</div>
    </div>
  </article>

</div>
