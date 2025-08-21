---
layout: themes
title: Themes
permalink: /themes/
---


<div>
  {% assign music = site.pages | where: "title", "Music" | first %}
<a href="{{ music.url | relative_url }}">Music</a>
</div>

<div>
  {% assign tvw = site.pages | where: "title", "The Vegetal World" | first %}
<a href="{{ tvw.url | relative_url }}">The Vegetal World</a>
</div>

