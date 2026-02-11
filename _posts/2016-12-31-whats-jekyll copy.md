---
layout: post
title: "Playing siinamota.mp3"
---

{% if site.baseurl %}
  {% assign music_path = "/assets/music/siinamota.mp3" | prepend: site.baseurl %}
{% else %}
  {% assign music_path = "/assets/music/siinamota.mp3" %}
{% endif %}

<audio controls preload="none">
  <source src="{{ music_path }}" type="audio/mpeg">
</audio>

[ Download {{ music_path | split: '/' | last }} ]({{ music_path }})
[ uppppp {{ music_path | split: '/' | last }} ]({{ music_path }})
[ Download {{ music_path | split: '/' | last }} ]