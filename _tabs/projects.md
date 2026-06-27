---
layout: page
icon: fa-solid fa-hat-wizard
order: 2
---

# Web Projects

This is just a collection of web projects I've made over the years

<div class="row row-cols-1 row-cols-md-1 row-cols-lg-2 g-4">
  {% for project in site.data.projects %}
    <div class="col">
      <div class="project-card h-100">
        <img src="{{ project.image }}" class="card-img-top mt-0" alt="{{ project.title }}">
        
        <div class="p-3">
          <h5 class="title">{{ project.title }}</h5>
          
          <p class="description">
            {{ project.description }}
          </p>

          <a href="{{ project.link }}" target="_blank" class="btn btn-secondary">
            View Project
          </a>
        </div>
      </div>
    </div>

{% endfor %}

</div>
