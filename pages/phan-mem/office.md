---
layout: page
show_meta: false
title: "Các phiên bản Office"
subheadline: "Phần mềm"
header:
   image_fullwidth: "header_unsplash_12.jpg"
permalink: "/phan-mem/office/"
---
<ul>
    {% for post in site.categories.office %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>