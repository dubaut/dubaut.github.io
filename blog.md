---
layout: default
---
\| {% for page in site.data.main_nav.pages %}[{{ page.title }}]({{ page.url }}) \| {% endfor %}

{% assign firstPost = site.posts.first %}

[Home](index.html)

## Blog.

### {{ firstPost.title }}
<p><a href="{{ firstPost.url }}">{{ firstPost.excerpt }}</a></p>