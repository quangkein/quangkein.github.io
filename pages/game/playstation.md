---
layout: page
show_meta: false
title: "Playstation"
subheadline: "Game"
header:
   image_fullwidth: "header_game.jpg"
permalink: "/game/playstation"
---
<ul>
    {% for post in site.categories.playstation %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>