---
layout: page
title: Products I've Built
permalink: /companies/
feature-img: "img/color.png"
---
  <div class="work">
    {% for project in site.portfolio limit:10 %}
    <div class="project">
        <a href="{{ project.url | prepend: site.baseurl }}">
        </a>
      <div class="project-description">
        <a href="{{ project.url | prepend: site.baseurl }}"><strong>{{ project.title }}</strong></a>
        <p>{{ project.short-description }}</p>
      </div>
    </div>
    {% endfor %}
  </div>