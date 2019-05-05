---
title: Experiments
permalink: "/Experiments/"
layout: page
---

<!-- <a href="/name">name</a> | <a href="https://github.com/PlatypodeCode/name">Git</a> -->

<div class="grid-display">
{% for experiment in site.data.experiments.experiments %}
  <div><span><h1><a href="https://git.platypodes.xyz/{{experiment.short}}">{{experiment.display}}</a></h1><a href="https://github.com/PlatypodeCode/{{experiment.short}}">Git</a></span></div>
{% endfor %}    
</div>
