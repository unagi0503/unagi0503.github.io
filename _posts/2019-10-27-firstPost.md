---
layout: post
title: "Hank Quinlan, Horrible Cop, Launches Site"
date: 2019-10-27
category: general
tags: [foo]
---

{% comment %}
=======================
The purpose of this snippet is to list all the tags you have in your site.
=======================
{% endcomment %}
{% for tag in tags %}
	<a href="#{{ tag | slugify }}"> {{ tag }} </a>
{% endfor %}

Well. Finally got around to putting this old website together. 
Neat thing about it - powered by [Jekyll](http://jekyllrb.com) and I can use Markdown to author my posts. 
It actually is a lot easier than I thought it was going to be.
