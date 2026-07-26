---
layout: page
icon: fa-solid fa-hat-wizard
order: 2
---

Several projects that I've worked on or solo created for the last several years.

# Web Applications

<div class="row row-cols-1 row-cols-md-2 row-cols-lg-2 mt-3 g-4">
  {% for project in site.data.web-projects %}
    <div class="col">
      <div class="project-card h-100">
        <img
          src="{{ project.image | relative_url }}"
          class="mt-0"
          alt="{{ project.title }}"
          loading="lazy"
          decoding="async"
        >

        <div class="content-container">
          <h5 class="title">{{ project.title }}</h5>

          <p class="description">
            {{ project.description }}
          </p>

          <a
            href="{{ project.link }}"
            target="_blank"
            rel="noopener noreferrer"
            class="project-button"
          >
            View Project
          </a>
        </div>
      </div>
    </div>

{% endfor %}

</div>

# Mobile Apps

<div class="row row-cols-1 row-cols-md-2 row-cols-lg-2 mt-3 g-4">
  {% for project in site.data.mobile-projects %}
    <div class="col">
      <div class="project-card h-100">
        <img
          src="{{ project.image | relative_url }}"
          class="mt-0"
          alt="{{ project.title }}"
          loading="lazy"
          decoding="async"
        >

        <div class="content-container">
          <h5 class="title">{{ project.title }}</h5>

          <p class="description">
            {{ project.description }}
          </p>

          <a
            href="{{ project.link }}"
            target="_blank"
            rel="noopener noreferrer"
            class="project-button"
          >
            View Project
          </a>
        </div>
      </div>
    </div>

{% endfor %}

</div>

# Game Dev

<div class="row row-cols-1 row-cols-md-2 row-cols-lg-2 mt-3 g-4">
  {% for project in site.data.game-projects %}
    <div class="col">
      <div class="project-card h-100">
        <img
          src="{{ project.image | relative_url }}"
          class="mt-0"
          alt="{{ project.title }}"
          loading="lazy"
          decoding="async"
        >

        <div class="content-container">
          <h5 class="title">{{ project.title }}</h5>

          <p class="description">
            {{ project.description }}
          </p>

          <a
            href="{{ project.link }}"
            target="_blank"
            rel="noopener noreferrer"
            class="project-button"
          >
            View Project
          </a>
        </div>
      </div>
    </div>

{% endfor %}

</div>

# Simulations

<div class="row row-cols-1 row-cols-md-2 row-cols-lg-2 mt-3 g-4">
  {% for project in site.data.simulation-projects %}
    <div class="col">
      <div class="project-card h-100">
        <img
          src="{{ project.image | relative_url }}"
          class="mt-0"
          alt="{{ project.title }}"
          loading="lazy"
          decoding="async"
        >

        <div class="content-container">
          <h5 class="title">{{ project.title }}</h5>

          <p class="description">
            {{ project.description }}
          </p>

          <a
            href="{{ project.link }}"
            target="_blank"
            rel="noopener noreferrer"
            class="project-button"
          >
            View Project
          </a>
        </div>
      </div>
    </div>

{% endfor %}

</div>
