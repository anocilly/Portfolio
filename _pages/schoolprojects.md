---
layout: default
title: Andrew Nocilly - Portfolio
permalink: /schoolprojects/
---

<div class="gallery-container">
  <div class="project-gallery">
    <div class="gallery-item">
      <a href="{{ "/schoolprojects/slf-design-project-mae-2250/" | relative_url }}">
        <img src="{{ "/assets/images/slf/slf.jpg" | relative_url }}" alt="SLF Design Project MAE 2250" />
        <p>SLF Design Project MAE 2250</p>
      </a>
    </div>
    {% for project in site.schoolprojects %}
        {% unless project.title == "SLF Client Pitch" or project.title == "SLF Functional Prototype" or project.title == "SLF Client Final Report" %}
        <div class="gallery-item">
                <a href="{{ project.url | relative_url }}">
                <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
                <p>{{ project.title }}</p>
                </a>
            </div>
        {% endunless %}
    {% endfor %}
  </div>
</div>