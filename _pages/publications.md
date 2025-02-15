---
layout: archive
title: "Publications"
permalink: /publications/
author_profile: true
---

{% include base_path %}

{% for post in site.publications reversed %}
  {% include archive-single.html %}
{% else %}
  <p>No publications found. Make sure they are in the <code>_publications</code> folder.</p>
{% endfor %}
