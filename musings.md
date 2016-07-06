---
layout: page
permalink: /musings/index.html
title: Musings
image:
  feature_url: http://techtohuman.s3.amazonaws.com/images/milena_keyboard.jpg 
  
---

At Tech to Human, we are fascinated by:

<ul>
	<li><strong> Experiments in teaching data & technology skills</strong> - particularly to NGO and journalist audiences. (Jump to: <a href="http://techtohuman.com/tags.html#Data 101">Data Posts</a>, <a href="http://techtohuman.com/tags.html#Jargon">Jargon Busting Posts</a>)</li>
	<li><strong>Facilitation for designing tech projects & understanding user needs</strong> (Jump to: <a href="http://techtohuman.com/tags.html#Facilitation">Facilitation Posts</a>, <a href="http://techtohuman.com/tags.html#Strategy">Strategy Posts</a>)</li>
	<li><strong>The intersection of technology and other sectors</strong> From politics to healthcare, exploring what happens when you add technology to the mix.</li> 
</ul>	

<p> 
<div class="well">

All posts are version controlled, meaning that you can see past edits, who they were changed by and when. For more information, see the <a href="http://techtohuman.com/version_controlled_thinking/">related blog post</a>.  

</div> 
</p>


<h1>  All Posts </h1>

<ul class="post-list">
{% for post in site.posts limit:100 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>

<nav class="browse-button" role="navigation">
<a href="/tags.html" class="btn" title="Browse by topic">Browse by topic</a>
</nav>
