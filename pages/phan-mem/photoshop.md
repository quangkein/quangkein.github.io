---
layout: page
show_meta: false
title: "Các phiên bản Photoshop"
subheadline: "Phần mềm"
header:
   image_fullwidth: "header_unsplash_12.jpg"
permalink: "/phan-mem/photoshop/"
---
<ul>
    {% for post in site.categories.photoshop %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>