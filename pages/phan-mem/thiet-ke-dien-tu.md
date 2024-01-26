---
layout: page
show_meta: false
title: "Các phần mềm thiết kế điện tử"
subheadline: "Phần mềm"
header:
   image_fullwidth: "header_unsplash_12.jpg"
permalink: "/phan-mem/thiet-ke-dien-tu/"
---
<ul>
    {% for post in site.categories.thiet-ke-dien-tu %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>