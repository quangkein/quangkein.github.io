---
layout: page
show_meta: false
title: "Game"
header:
   image_fullwidth: "header_game.jpg"
permalink: "/game/"
---
<ul>
    {% for post in site.categories.game %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>