---
title: Projects for Fun
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

  <!-- Two-column layout -->
  <div style="
    display: flex;
    gap: 24px;
    flex-wrap: wrap;
    align-items: flex-start;
  ">

    <!-- Text column -->
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

    <!-- Video column -->
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

  <!-- Full-width text BELOW the columns -->
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
    <strong>SanityChronicles ✨</strong> is a Shiny extension of the original SanityApp, written with R,
    focused on richer and easier exploration, visualizations, and playful interaction with personal mood data.
  </p>

  <p>
    This version offers an easier way of employing a mood-logging app on your own device for personal usage,
    and for engaging with wellbeing data through interactive views, summaries, and analysis-oriented representations.
  </p>

  <p style="opacity: 0.85;">
    The Shiny Edition is currently in development and may evolve in scope, form, or platform.
  </p>

  <!-- External link -->
  <p style="margin-top: 12px;">
    🚀 <a href="https://friederikequint-shinychronicles-app.share.connect.posit.cloud"
          target="_blank" rel="noopener">
      Open the Shiny App in a new tab
    </a>
  </p>

  <!-- Embedded Shiny app -->
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

</div>

<p style="margin-top: 12px; font-style: italic; opacity: 0.8;">
  Status: still exploring · Form: deliberately open · Confidence: curious
</p>
