---
layout: default
title: Blog
permalink: /blog/
---

Congratulations. You found my blog.  Ok this is not a real blog but rather a collection of unrelated bits and pieces that I deemed useful.


# {{ page.title }}

<ul class="posts">

	{% for post in site.posts %}
	<li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>


