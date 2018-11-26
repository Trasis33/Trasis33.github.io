---
layout: post
title:  "Implementing Open Graph"
date:   2018-11-26 21:31:14 +0100
categories: jekyll update
comments: true
---

## What is Open Graph and how do I make use of it?

*Open Graph* is practically a universal standard for sharing webpages on social media platforms. With *Open Graph* it let's you preview information and content when linking a webpage. By using *Open Graph*-specific meta tags in a page `<head>` you can send properties to be shown on the link.

I implemented it by adding meta tags to a copy of `head.html` in my `_includes`-folder with the following:
```
  <meta property="og:title" content="{{ page.title }}" />
  <meta property="og:type" content="website" />
  <meta property="og:url" content="{% capture url_path %}{{site.url}}{{page.url}}{% endcapture %}" />
  <meta property="og:image" content="/src/assets/pics/Avatar.png" />
```