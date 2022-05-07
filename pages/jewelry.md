---
layout: page
show_meta: false
title: "Links to posts about jewelry"
subheadline: "Specific organisations of jewelry"
header:
   image_fullwidth: "banner.jpg"
permalink: "/jewelry/"
---
<ul>
    {% for post in site.categories.jewelry %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>