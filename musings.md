---
layout: page
permalink: /musings/index.html
title: Musings
image:
  feature_url: http://techtohuman.s3.amazonaws.com/images/product_manager_title.png 
  
---

At Tech to Human, we focus on:

<ul>
	<li><strong>Product Management</strong> (<a href="http://techtohuman.com/tags.html#Product">Take me to product posts</a>)</li>
	<li><strong> Talking about technology in plain language and other ways to make it more accessible</strong> (Jump to: <a href="http://techtohuman.com/tags.html#Jargon">Jargon Busting Posts</a>, <a href="http://techtohuman.com/tags.html#Data 101">Data Posts</a>, <a href="http://techtohuman.com/tags.html#Facilitation">Facilitation Posts</a>)</li>
	<li><strong>NGO tech</strong> (<a href="http://techtohuman.com/tags.html#Strategy">Take me to NGO Tech Posts</a>)</li>
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
