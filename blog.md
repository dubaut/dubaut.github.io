{% assign firstPost = site.posts.first %}

## Blog



{% for post in site.posts %}
### {% firstPost.title %}
{% endfor %}

<ul>
    {% for post in site.posts %}
    <li>
        <a href="{{ post.url }}">{{ post.title }}</a>
        <p>{{ post.excerpt }}</p>
    </li>
    {% endfor %}
</ul>

1