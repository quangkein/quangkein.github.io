---
layout: page
show_meta: false
title: "Học tập"
subheadline: "Tài nguyên"
header:
   image_fullwidth: "knowledge.jpg"
permalink: "/tai-nguyen/hoc-tap"
---
<ul>
    {% for post in site.categories.hoc-tap %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>