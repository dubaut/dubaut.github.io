---
layout: content
---
{% assign firstPost = site.posts.first %}

[Home](index.html)

## Blog.

### {{ firstPost.title }}
<p><a href="{{ firstPost.url }}">{{ firstPost.excerpt }}</a></p>