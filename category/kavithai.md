---
layout: page
date: 2013-12-12 00:00:00 +0530
title: 
permalink: /category/kavithai/
---

<div>
    <a href="{{ site.url }}">முகப்பு</a>&nbsp;&gt;&nbsp;<a href="{{ site.url }}/categories">தொகுப்புகள்</a>&nbsp;&gt;&nbsp;<a href="{{ site.url }}/category/kavithai/">கவிதை</a>
  	
	<ul>
    {% for post in site.categories.kavithai %}
		<li><p><a href="{{ post.url }}">{{ post.title }}</a></p></li>
    {% endfor %}
	</ul>
</div>
