---
layout: default
title: Blogging Like a Hacker
description: Stuff
---

## Welcome to GitHub Pages

{% for post in site.posts %}
### <a href="{{ post.url }}">{{ post.title }}</a>
{{ post.excerpt }}
{% endfor %}

Test.
