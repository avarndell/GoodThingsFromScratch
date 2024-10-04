---
galleries:
  - title: Link to homepage
    image: /uploads/album/1.jpg
    url: /
  - title: Link to image gallery
    image: /uploads/album/2.jpg
    url: /without-plugin/image-gallery
layout: page
title: Inspiration
permalink: /Inspiration/
image: '/images/25.jpg'
---

{% if page.galleries %}{% include image-gallery-index.html %}{% endif %}
