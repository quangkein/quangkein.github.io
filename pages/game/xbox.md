---
layout: page
show_meta: false
title: "Xbox"
subheadline: "Game"
header:
   image_fullwidth: "header_game.jpg"
permalink: "/game/xbox"
---
<ul>
    {% for post in site.categories.xbox %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>