---
layout: default
title: Blog
permalink: /blog/
---

I am interested in genealogy. This side shows some of my research results (in German).


# {{ page.title }}

<ul class="posts">

	{% for post in site.posts %}
	<li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>


