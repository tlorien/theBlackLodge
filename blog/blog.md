---
layout: blog
title: "Blog"
permalink: /blog/
---
<ul>
{% for post in site.posts %}
  <div>
    <h2><a href="{{ site.baseurl }}{{ post.url }}">{{ post.title }}</a></h2>
    <p>{{ post.excerpt }}</p>
  </div>
{% endfor %}
</ul>
