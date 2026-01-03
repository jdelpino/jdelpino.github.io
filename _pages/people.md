---
layout: page
permalink: /people/
title: People
subtitle: Group members
description: Group members
nav: true
nav_order: 7
---

{% assign cv = site.data.cv %}
{% assign gi = cv | where: "title", "General Information" | first %}
{% assign langs = gi.contents | where: "name", "Languages" | first %}
{% assign edu = cv | where: "title", "Education" | first %}
{% assign phd = edu.contents | first %}
{% assign visit = edu.contents | where: "title", "Visiting Research Fellow" | first %}

<div class="row g-4">

  <!-- Javier -->
  <div class="col-12 col-sm-6 col-md-4 col-lg-3">
    <div class="card h-100 shadow-sm">
      <a href="{{ '/cv/' | relative_url }}" style="text-decoration:none;">
        <img
          src="{{ 'assets/img/prof_pic.jpg' | relative_url }}"
          class="card-img-top"
          alt="Javier del Pino"
          loading="lazy"
        >
      </a>
      <div class="card-body">
        <h5 class="card-title mb-1">
          <a href="{{ '/cv/' | relative_url }}">Javier del Pino</a>
        </h5>
        <p class="card-text mb-2"><small>Group leader · IFIMAC–UAM</small></p>

        <div class="d-flex flex-wrap gap-2 mb-2">
          <a class="btn btn-sm btn-outline-secondary" href="{{ '/cv/' | relative_url }}">CV page</a>
          <a class="btn btn-sm btn-outline-secondary" href="{{ '/assets/pdf/CV_JdP.pdf' | relative_url }}">CV (PDF)</a>
        </div>

        <ul class="mb-0" style="padding-left: 1.1rem;">
          {% if phd %}<li><small>{{ phd.title }} ({{ phd.year }})</small></li>{% endif %}
          {% if visit %}<li><small>{{ visit.institution }} ({{ visit.year }})</small></li>{% endif %}
          {% if langs %}<li><small>Languages: {{ langs.value }}</small></li>{% endif %}
        </ul>
      </div>
    </div>
  </div>

  <!-- Alejandro -->
  <div class="col-12 col-sm-6 col-md-4 col-lg-3">
    <div class="card h-100 shadow-sm">
      <a href="{{ '/people/alejandro-s-gomez/' | relative_url }}" style="text-decoration:none;">
        <img
          src="https://scholar.googleusercontent.com/citations?view_op=medium_photo&user=Z-_obTUAAAAJ&citpid=1"
          class="card-img-top"
          alt="Alejandro S. Gómez"
          loading="lazy"
        >
      </a>
      <div class="card-body">
        <h5 class="card-title mb-1">
          <a href="{{ '/people/alejandro-s-gomez/' | relative_url }}">Alejandro S. Gómez</a>
        </h5>
        <p class="card-text mb-0"><small>PhD student (IFIMAC)</small></p>
      </div>
    </div>
  </div>

</div>
