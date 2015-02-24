---
layout: page
permalink: /musings/index.html
title: Musings
tags: [Tech translation, Tech translator, Technology, Jargon, Rants]
image:
  feature_url: http://techtohuman.s3.amazonaws.com/images/milena_keyboard.jpg 
  
---

# This is not a blog...

It is a series of thoughts on how to make technology more accessible to a variety of audiences. 

All the posts are version controlled, meaning that you can see past edits, who they were changed by and when. E.g. [See the history of this page](https://github.com/lucychambers/lucychambers.github.io/blob/master/musings.md). 

## Why do I do this, I hear you ask... 

![Version-Controlled-Thinking](http://techtohuman.s3.amazonaws.com/images/vct_3.jpeg)

### Reason 1: As an accountability mechanism. I have opinions and I update them in light of new evidence. 

... because one of my ways of learning is to write down what I think and share it with smart people. If those smart people convince me to change my opinion, I change it. If they don't, I leave it. 

It is hard to show how thoughts and opinions change over time. I also think it is humbling to remember that you have not always held the enlightened opinions you hold now.

<iframe width="560" height="315" src="https://www.youtube.com/embed/-Wb1jkcKG94" frameborder="0" allowfullscreen></iframe>

### Reason 2: To prevent myself from clogging the internet with more junk. Junk makes people angry. 

I there is a lot of outdated junk on the internet and that makes some technical topics even harder to navigate. I believe that if we do not clear up after ourselves, then this happens: 

![Wrong on the Internet](http://imgs.xkcd.com/comics/duty_calls.png)

<small> Duty Calls by XKCD CC-BY-NC. </small> 

I mean to cause you no pain in reading this blog, dear reader. If I have got something wrong, please email me on lucy [at] fedia.net and we'll talk!  

### Reason 3: I aspire to write concisely 

<blockquote>“If I had more time I would have written you a shorter letter” </blockquote>

Time is precious, I don't want to waste yours. Occasionally, I will work out a much more consice way to explain something and go in and change it. 

#### How to use the version control 

You do not have to ever look back at the history if you don't need to, however, I give you this option for a few reasons. 

* Maybe you referenced something and now can't find the quote because I changed that text? 
* Maybe you preferred a previous version of a diagram? 
* Maybe you just want to see how many times I changed my mind. (I don't recommend this for the earlier posts, it was a lot!)

In this case, simply: 

1. Visit the [Github repository](https://github.com/lucychambers/lucychambers.github.io) for the site and find the page you are looking for. Or, if you are looking for an update on a particular post, go directly to the [posts](https://github.com/lucychambers/lucychambers.github.io/tree/master/_posts/articles).  
2. Select the post or page and click on the *'History'* button to see a list of changes made to that post. You can click through on a particular change if you are interested in more details. 

## The Series

<div class="well"> 

<h3> The 'So What?' series </h3> 

I once had a professor who had a big green pen. If ever anyone in our class wrote something that they deemed self-evident, but probably was not self explanatory. They would get a big green 'So What?' stamped at the top of their page. 

I have seen many excellent tutorials on many technical topics on the internet. However, hardly any of them really answer the questions: 'So what?' 'Why should I care?'. 

When working at School of Data, we had two types of courses: 

<ol> 
	<li> <strong> Inspirational Courses </strong> -  Focussing on why people should get excited about learning a new skill and how they would be able to use it.  </li>
	<li> <strong> How to Courses </strong> - The hands on, nitty-gritty of how to use a particular tool or skill.  </li> 
</ol>

It was pointless attempting the latter without the former.  The "So What?" series is an editorial; my best attempt at showing why you might want to care about a particular topic. 

</div> 


# Posts

<ul class="post-list">
{% for post in site.posts limit:10 %} 
  <li><article><a href="{{ site.url }}{{ post.url }}">{{ post.title }} <span class="entry-date"><time datetime="{{ post.date | date_to_xmlschema }}">{{ post.date | date: "%B %d, %Y" }}</time></span></a></article></li>
{% endfor %}
</ul>

<nav class="browse-button" role="navigation">
<a href="/tags.html" class="btn" title="Browse by topic">Browse by topic</a>
</nav>
