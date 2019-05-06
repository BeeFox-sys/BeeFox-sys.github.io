---
title: Interactive Stories
permalink: "/Stories/"
layout: page
---

# Interactive stories
Created with <a href="https://twinery.org">twine</a>

<div class="grid-display">
  {% for story in site.data.stories.stories %}
  <a href="{{story.link | relative_url}}"><div style="height:auto;"><span class="story">
  <h3>{{story.name}}</h3>
  <hr>
  <h5>{{story.blurb}}</h5>
  </span></div></a>
  {% endfor %}

{% unless site.data.stories.stories[0]%}
  Nothings here!
{% endunless %}
</div>
