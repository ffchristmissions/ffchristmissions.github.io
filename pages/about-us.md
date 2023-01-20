---
layout: page
subheadline: "About Us"
title: "We are Fishers for Christ"
teaser: "Fishers for Christ ministries is made up of a Christians set out to be fishers of men. fwefew/n wfefew/n wfewfe<br> weffew<br> "
header:
    title: header with text
    image_fullwidth: header_unsplash_12.jpg

permalink: "/about-us/"
---
<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
