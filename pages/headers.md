---
layout: page
show_meta: false
subheadline: " "
title: "研究团队"
teaser: "我们拥有一支强大的研发队伍"
header:
   image_fullwidth: "header_unsplash_5.jpg"
permalink: "/headers/"
---
<ul>
    {% for post in site.tags.teacher %}
    <li><a href="{{ site.url }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>