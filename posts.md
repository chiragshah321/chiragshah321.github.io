---
layout: page
title: Posts
permalink: /posts/
feature-img: "img/color.png"
---
<div class="work">
    {% for post in site.post limit:10 %}
    <div class="post">
        <a href="{{ post.url | prepend: site.baseurl }}">
        </a>
      <div class="post-description">
        <a href="{{ post.url | prepend: site.baseurl }}"><strong>{{ post.title }}</strong></a>
        <p>{{ post.short-description }}</p>
      </div>
    </div>
    {% endfor %}
  </div>


