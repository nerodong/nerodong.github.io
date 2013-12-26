---
layout: page
title: Something about Me
tagline: Supporting tagline
---
{% include JB/setup %}
{% include JB/analytics-providers/google %}
Nero Dong is an active data envagelist on Internet playground. His background mainly based on
Communication Science and Market Research. Currently He is hunting for job in Shenzhen.
His spectrum of interest lies in media & psychology, society and new media, Free flow of 
information, spatial data products and information visualization. 

## Current Researches and Works
    

    
## Nero's Post

<ul class="posts">
  {% for post in site.posts %}
    <li><span>{{ post.date | date_to_string }}</span> &raquo; <a href="{{ BASE_PATH }}{{ post.url }}">{{ post.title }}</a></li>
  {% endfor %}
</ul>

## Projects & Nice Try-out

This theme is still unfinished. If you'd like to be added as a contributor, [please fork](http://github.com/plusjade/jekyll-bootstrap)!
We need to clean up the themes, make theme usage guides with theme-specific markup examples.


