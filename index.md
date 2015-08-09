---
title: COMP 422
layout: default-vertical

categories:
- general
- site

tags: general site home
published: true
summary: Software Development for Wireless and Mobile Devices, Fall 2015
---

Welcome to the course website for COMP 422, Software Development for Wireless and Mobile Devices. 

This course is offered by the [Department of Computer Science](http://www.luc.edu/cs/) at [Loyola University Chicago](http://www.luc.edu).

***

#### Recent Updates
{% for post in site.posts limit: 5 %}
* {{ post.date | date_to_string }} | [{{ post.title }}]({{ post.url }})

  {{ post.summary }}
{% endfor %}




