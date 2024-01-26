---
layout: page
show_meta: false
title: "Các phiên bản Windows"
subheadline: "Phần mềm"
header:
   image_fullwidth: "header_unsplash_12.jpg"
permalink: "/phan-mem/windows/"
---
<ul>
    {% for post in site.categories.windows %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>