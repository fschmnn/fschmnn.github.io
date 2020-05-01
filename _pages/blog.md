---
layout: default
title: Blog
permalink: /blog/
---

here is a selection of random thoughts

# {{ page.title }}

<ul class="posts">

	{% for post in site.posts %}
	<li><span>{{ post.date | date_to_string }}</span> » <a href="{{ post.url }}" title="{{ post.title }}">{{ post.title }}</a></li>
	{% endfor %}
</ul>


<iframe src="https://www.google.com/maps/d/embed?mid=1witWPze5PWBg_l37o1TfOymWuv_S6js8" width="800" height="494"></iframe>