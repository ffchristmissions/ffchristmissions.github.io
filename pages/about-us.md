---
layout: page
subheadline: "About Us"
title: "We are Fishers for Christ Missions"
teaser: "We are a collective of Christians who believe in sharing the good news of the gospel of the Lord Jesus Christ. We believe God sent his only begotten Son into the world in the person of Jesus Christ to reconcile people back to God. <br><br>"
header:
    title: Fishers for Christ Missions
    image_fullwidth: header_unsplash_12.jpg

permalink: "/about-us/"
---
<ul>
    {% for post in site.tags.header %}
    <li><a href="{{ site.url }}{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></li>
    {% endfor %}
</ul>
