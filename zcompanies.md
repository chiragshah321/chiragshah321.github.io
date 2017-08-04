---
layout: page
title: Products
permalink: /companies/
feature-img: "img/color.png"
---
  <div class="work">
    {% for product in site.product limit:10 %}
    <div class="project">
        <a href="{{ product.url | prepend: site.baseurl }}">
        </a>
      <div class="project-description">
        <a href="{{ product.url | prepend: site.baseurl }}"><strong>{{ product.title }}</strong></a>
        <p>{{ product.short-description }}</p>
      </div>
    </div>
    {% endfor %}
  </div>