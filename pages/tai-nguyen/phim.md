---
layout: page
show_meta: false
title: "Phim"
subheadline: "Tài nguyên"
header:
   image_fullwidth: "knowledge.jpg"
permalink: "/tai-nguyen/phim"
---
<ul>
    {% for post in site.categories.tai-nguyen-phim %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>