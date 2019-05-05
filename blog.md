---
title: Blogs
permalink: "/Blog/"
layout: page
---

# My Blogs

<div class="grid-display">
  {% for link in site.data.blogs.links %}
  <a href="{{link.link}}"><div><span><h1>{{link.display}}</h1></span></div></a>
  {% endfor %}
</div>
