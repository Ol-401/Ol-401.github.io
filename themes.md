---
layout: page
title: Themes
permalink: /themes/
---
<head>
  <!-- Google tag (gtag.js) -->
  <script async src="https://www.googletagmanager.com/gtag/js?id=G-1XMXKD3CHE"></script>
  <script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());

  gtag('config', 'G-1XMXKD3CHE');
  </script>
</head>

<div>
  {% assign music = site.pages | where: "title", "Music" | first %}
<a href="{{ music.url | relative_url }}">Music</a>
</div>

<div>
  {% assign tvw = site.pages | where: "title", "The Vegetal World" | first %}
<a href="{{ tvw.url | relative_url }}">The Vegetal World</a>
</div>

