---
layout: page
show_meta: false
title: "Chỉnh sửa video"
subheadline: "Phần mềm"
header:
   image_fullwidth: "header_unsplash_12.jpg"
permalink: "/phan-mem/chinh-sua-video/"
---
<ul>
    {% for post in site.categories.chinh-sua-video %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>