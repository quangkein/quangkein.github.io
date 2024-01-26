---
layout: page
show_meta: false
title: "App xem phim trên Android"
subheadline: "App android"
header:
   image_fullwidth: "header_unsplash_12.jpg"
permalink: "/android/phim/"
---
<ul>
    {% for post in site.categories.android-phim %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>