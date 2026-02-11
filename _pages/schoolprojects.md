---
layout: default
title: Andrew Nocilly - Portfolio
permalink: /schoolprojects/
---

<div class="gallery-container">
  <div class="project-gallery">
    {% for project in site.schoolprojects %}
        <div class="gallery-item">
            <a href="{{ project.url | relative_url }}">
            <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
            <p>{{ project.title }}</p>
            </a>
        </div>
    {% endfor %}
  </div>
</div>