---
layout: post
title:  "Robots and humans"
date:   2018-11-26 20:19:43 +0100
categories: jekyll update
comments: true
---
{% seo %}
## What is robots.txt and how have I configured it for my site?

*robots.txt* is a file with instructions for search engines and bots telling them what I would like for them to access or not to access on my site. It's not a safeguard, it just kindly asks them to respect what is written in the robots.txt. If they are malicious it does nothing to stop them from reading all of the files.

My *robots.txt* is set up lite this:
```
User-agent: *
Disallow: /
```
This means I want my entire site excluded from searches and indexing, and asking them *politely* to do what I ask.


## What is humans.txt and how have I configured it for my site?

*humans.txt* is a file for the people visiting my site, where they can find information about the author of the site, and what information the author wishes to share, like for example name, contact info, standards used, programs used and when the latest update was made to the site.

My *humans.txt* is set up like this:
```

/* TEAM */

Your title: Fredrik Langå

Site: localhost:4000 for now

Twitter: frlanga

Github: Trasis33

Location: Kalmar, Sweden

/* SITE */

Last update: 2018/11/26 

Standards: HTML5, CSS3

Components: jekyll, sass

Software: Visual Studio Code
```
