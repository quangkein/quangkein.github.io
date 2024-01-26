---
layout: page
show_meta: false
title: "Phần mềm máy tính"
subheadline: "Phần mềm free & full crack"
header:
   image_fullwidth: "header_unsplash_12.jpg"
permalink: "/phan-mem/"
---
<ul>
    {% for post in site.categories.phan-mem %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>