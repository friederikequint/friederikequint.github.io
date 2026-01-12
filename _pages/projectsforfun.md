---
title: Fun Projects
permalink: /projectsforfun/
---

This page hosts a small collection of exploratory side projects developed alongside my academic work. If you have questions, ideas, or would like to discuss any of these projects, feel free to reach out via <a href="mailto:friederike.quint@tum.de">email</a>.

These projects are driven by curiosity, experimentation, and a desire to build lightweight, usable tools outside formal research contexts. 

(Disclaimer: I am not a developer, but I am always keen to learn about and explore new ways of thinking, technologies, and more :) )

<hr />

<h3><strong>Project: SanityApp</strong></h3>

<div style="
  margin-top: 16px;
  padding: 16px;
  border: 1px solid rgba(0,0,0,0.08);
  border-radius: 14px;
  background: rgba(0,0,0,0.02);
">

  <div style="
    display: flex;
    gap: 24px;
    flex-wrap: wrap;
    align-items: flex-start;
  ">

    <div style="flex: 1; min-width: 260px;">
      <p style="margin-top: 0;">
        <strong>SanityApp</strong> is a simple iOS mood-tracking application built with Swift.
        It allows users to log how they’re feeling, reflect on past entries, and gain a lightweight overview
        of their emotional wellbeing over time. 
      </p>

      <p>
        The app is intentionally designed as a clean, extendable starting point for personal use,
        experimentation, or further development of wellbeing-focused mobile applications.
      </p>

      <p><strong>What the app does:</strong></p>
      <ul>
        <li>Record daily mood entries (daily mood, stress level, optional notes)</li>
        <li>Review previously logged moods</li>
        <li>Reflect on emotional patterns over time</li>
        <li>Use a lightweight, private self-reflection tool</li>
        <li>Download your data for further analysis</li>
      </ul>
    </div>

    <div style="flex: 1; min-width: 300px;">
      <video
        controls
        preload="metadata"
        playsinline
        poster="{{ '/assets/SanityApp-preview.png' | relative_url }}"
        style="width: 100%; border-radius: 12px;"
      >
        <source src="{{ '/assets/Updated Showcasing SanityApp.mp4' | relative_url }}" type="video/mp4">
        Your browser does not support the video tag.
      </video>

      <p style="
        margin-top: 6px;
        font-size: 0.85em;
        opacity: 0.7;
        text-align: right;
      ">
        © Friederike Quint
      </p>
    </div>

  </div>

  <div style="margin-top: 16px;">
    <p style="margin-bottom: 0;">
      The full codebase is available as a <strong>public GitHub repository</strong>.
      The project is free to use, fork, and extend.
    </p>

    <p style="margin-top: 8px;">
      🔗 <a href="https://github.com/friederikequint/SanityApp/tree/main" target="_blank" rel="noopener">
        View SanityApp on GitHub
      </a>
    </p>
  </div>

</div>

<p style="margin-top: 12px; font-style: italic; opacity: 0.8;">
  Status: done for now :)
</p>

<hr />

<h3><strong>Project: ✨ SanityApp Shiny Edition ✨</strong></h3>

<div style="
  margin-top: 16px;
  padding: 16px;
  border: 1px solid rgba(0,0,0,0.08);
  border-radius: 14px;
  background: rgba(0,0,0,0.02);
">

 <p style="margin-top: 0;">
  <strong>SanityApp Shiny Edition ✨</strong> (also called <em>Sanity Chronicles</em>) is a mobile-friendly
  Shiny application for daily mood and stress tracking, built with R and designed for private,
  lightweight self-reflection.
</p>

<p>
  The app allows users to log a single daily entry within a defined evening time window,
  explore their emotional states through calendar and trend views, and export their data
  for personal reflection or further analysis.
</p>

<p><strong>What the app does:</strong></p>
<ul>
  <li>Record one mood and stress entry per day (with optional notes)</li>
  <li>Restrict entries to a defined daily time window (evening reflection)</li>
  <li>Visualize moods across a yearly calendar and trend plots</li>
  <li>Support private (owner) and public demo (guest) usage modes</li>
  <li>Export entries as CSV or JSON files</li>
  <li>Run locally or with persistent storage via a database backend</li>
</ul>

<p style="opacity: 0.85;">
  The Shiny Edition is intentionally built as a flexible, extendable starting point for
  experimenting with personal wellbeing data, Shiny-based interfaces, and lightweight
  self-tracking tools.
</p>


  <p style="margin-top: 12px;">
    🚀 <a href="https://friederikequint-shinychronicles-app.share.connect.posit.cloud"
          target="_blank" rel="noopener">
      Open the Shiny App in a new tab
    </a>
  </p>

  <div style="margin-top: 16px;">
    <iframe
      src="https://friederikequint-shinychronicles-app.share.connect.posit.cloud"
      style="
        width: 100%;
        height: 720px;
        border: 1px solid rgba(0,0,0,0.08);
        border-radius: 12px;
        background: white;
      "
      loading="lazy"
      allow="clipboard-read; clipboard-write"
    ></iframe>

    <p style="
      margin-top: 6px;
      font-size: 0.85em;
      opacity: 0.7;
      text-align: right;
    ">
      If the embed feels cramped (especially on mobile), opening it in a new tab works best.
    </p>
  </div>

  <div style="margin-top: 16px;">
    <p style="margin-bottom: 0;">
      The full Shiny app codebase is available as a <strong>public GitHub repository</strong>.
      The project is free to use, fork, and extend.
    </p>

    <p style="margin-top: 8px;">
      🔗 <a href="https://github.com/friederikequint/ShinyChronicles-app"
            target="_blank" rel="noopener">
        View SanityApp Shiny Edition on GitHub
      </a>
    </p>
  </div>

</div>

<p style="margin-top: 12px; font-style: italic; opacity: 0.8;">
  Status: happy, done for now, and still open for changes :)
</p>
