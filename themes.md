---
layout: themes
title: Themes
permalink: /themes/
---

{% assign music = site.pages | where: "title", "Music" | first %}
<a href="{{ music.url | relative_url }}">Music</a>

{% assign The Vegetal World = site.pages | where: "title", "The Vegetal World" | first %}
<a href="{{ The Vegetal World.url | relative_url }}">The Vegetal World</a>