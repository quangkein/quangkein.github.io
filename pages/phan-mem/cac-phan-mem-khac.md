---
layout: page
show_meta: false
title: "Các phần mềm khác"
subheadline: "Phần mềm"
header:
   image_fullwidth: "header_unsplash_12.jpg"
permalink: "/phan-mem/cac-phan-mem-khac/"
---
<ul>
    {% for post in site.categories.cac-phan-mem-khac %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>