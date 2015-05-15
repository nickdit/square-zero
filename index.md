---
layout: page
title: Square Zero Project
tagline: 
---
{% include JB/setup %}

Work in progress. For a final version please come back in 10 years.

## Introduction

Humanity's present shape is determined by a few very specific events and decisions made in the last 12.000 years. It is possible that there are other models in which we could have ended up living. This project is both a methapysical and a concrete exploration on the possibility of deconstructing and reconstructing all dimensions of human life.

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>


