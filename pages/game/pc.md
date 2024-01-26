---
layout: page
show_meta: false
title: "PC"
subheadline: "Game"
header:
   image_fullwidth: "header_game.jpg"
permalink: "/game/pc"
---
<ul>
    {% for post in site.categories.game-pc %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>