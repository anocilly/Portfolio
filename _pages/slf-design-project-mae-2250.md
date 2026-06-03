---
layout: default
title: SLF Design Project MAE 2250
permalink: /schoolprojects/slf-design-project-mae-2250/
---

# SLF Design Project MAE 2250

In MAE 2250, a sophomore design lab course, we were tasked with designing a solution to the presence of invasive spotted lanternflies in New York state's vineards. My group and I designed a scraper to remove spotted lanternfly egg masses from surfaces such as walls, trees, and other outdoor structures while collecting the removed material.
Our functional prototype is a telescoping mechanical scraper designed to facilitate manual methods of reaching high locations and removing egg masses. Feel free to explore the links below, containing the documentation of our design process, prototyping rounds, and testing results.

<div class="gallery-container">
  <div class="project-gallery">

    {% assign desired_order = "SLF Client Pitch|SLF Functional Prototype|SLF Client Final Report" | split: "|" %}

    {% for title in desired_order %}
      {% for project in site.schoolprojects %}
        {% if project.title == title %}
          <div class="gallery-item">
            <a href="{{ project.url | relative_url }}">
              <img src="{{ project.image | relative_url }}" alt="{{ project.title }}" />
              <p>{{ project.title }}</p>
            </a>
          </div>
        {% endif %}
      {% endfor %}
    {% endfor %}

  </div>
</div>