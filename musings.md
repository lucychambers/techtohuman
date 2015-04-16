---
layout: page
permalink: /musings/index.html
title: Musings
image:
  feature_url: http://techtohuman.s3.amazonaws.com/images/milena_keyboard.jpg 
  
---

# This is not a blog

It is a series of thoughts on how to make technology more accessible to a variety of audiences. 

All the posts are version controlled, meaning that you can see past edits, who they were changed by and when. For more information, see the [related blog post](http://techtohuman.com/version_controlled_thinking/).  

<a name="topics">

### Topics covered at Tech to Human:

<ul>
	<li><strong> Experiments in teaching data skills</strong> - particularly for NGO and journalist audiences. (Jump to: <a href="http://techtohuman.com/tags.html#Data 101">Data Posts</a>, <a href="http://techtohuman.com/tags.html#Jargon">Jargon Busting Posts</a>)</li>
	<li><strong>Facilitation for strategising & planning tech projects</strong> - particularly building products that address real user needs. (Jump to: <a href="http://techtohuman.com/tags.html#Facilitation">Facilitation Posts</a>, <a href="http://techtohuman.com/tags.html#Strategy">Strategy Posts</a>)</li>
	<li><strong>Intersections</strong> It is at the mid point between extremes, or at meeting points of traditionally different disciplines, that we learn. A technique which has been tried and tested in one discipline may be a revalation or a total belly flop in another. Intersections which currently interest me are: </li>
	<ul> 
		<li> <em>Non-profit x for-profit</em> - both have the potential to change the world but vastly different approaches, what can they learn from each other? </li>
		<li> <em>Open x Privacy</em> - commonly (incorrectly) seen as polar opposites </li>
		<li> <em>Online x Traditional Community Organising</em> - what motivates people to take action and what does that mean for modern campaigning?</li> 
	</ul>
</ul>	


# All Posts

<ul class="post-list">
{% for post in site.posts limit:100 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>

<nav class="browse-button" role="navigation">
<a href="/tags.html" class="btn" title="Browse by topic">Browse by topic</a>
</nav>
