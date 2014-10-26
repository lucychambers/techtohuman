---
layout: page
permalink: /musings/index.html
title: Musings
tags: [Tech translation, Tech translator, Technology, Jargon, Rants]
image:
  feature_url: https://s3-eu-west-1.amazonaws.com/techtohuman/images/IMG_0693_cropped.JPG 
  
---

Musings are learning-out-loud, version controlled thoughts on particular topics particularly on how to make technology more accessible to a variety of audiences. 

Why version-controlled? I hear you ask, well... 

![Version-Controlled-Thinking](http://techtohuman.s3.amazonaws.com/vct.png)

<ul class="post-list">
{% for post in site.posts limit:10 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>