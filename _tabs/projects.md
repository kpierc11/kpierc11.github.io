---
layout: page
icon: fa-solid fa-hat-wizard
order: 2
---

# Web Projects

This is just a collection of web projects I've made over the years.

<div class="row row-cols-1 row-cols-md-2 row-cols-lg-2 g-4">
  {% for project in site.data.projects %}
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
