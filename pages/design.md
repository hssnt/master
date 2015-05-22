---
layout: page
show_meta: false
title: "研究方向"
subheadline: "物联网的时代"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/design/"
---
<ul>
    {% for post in site.categories.research %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>