---
layout: home
---

<i>Hello! I am Fiona and here are some of my works!</i>

<div class="grid-display">
  {% for link in site.data.homelinks.links %}
  <a href="{{link.link}}"><div><span><h1>{{link.display}}</h1></span></div></a>
  {% endfor %}
</div>
