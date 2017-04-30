---
layout: post
permalink: /user_stories_jtbd
title: Hacking User Stories and Jobs to be Done    
tags: [Strategy]
image: 
  feature_url: http://techtohuman.s3.amazonaws.com/images/feature_maze.jpg

---

**This post will be useful to you if**: you have used [user stories](https://en.wikipedia.org/wiki/User_story) or [jobs stories / jobs to be done](https://jtbd.info/replacing-the-user-story-with-the-job-story-af7cdee10c27) to communicate a user need to a development team and are interested in ways to broaden your expressiveness in the communication. 

# Prior knowledge 

I am going to assume that you know why a "story" style template is commonly used as communication tool in development teams to guide what should be built. If not, I suggest having a look at [this article](http://www.usabilitycounts.com/2013/10/11/why-i-love-user-stories/) first to understand some of the benefits.  

Jobs to be done appears to be less well known as a format, so I also recommend <a href = "https://jtbd.info/replacing-the-user-story-with-the-job-story-af7cdee10c27">this article</a> on the merits of job stories vs the traditional user story. 

Here, we will be paying attention to where each model puts emphasis and encouraging you to hack the models to get what you need from them. 

# A refresher on the two formats

To begin, let us quickly remind ourselves of the two formats we are contrasting: 

## The user story follows this format: 

<div class="well"> <strong>As a</strong> [...]
<strong>I want to</strong> [...]
<strong>So that</strong> [...].</div>

For example: **As a** teacher, **I want to** compute an average of a pupil's test scores for pupils in my class **so that** it is obvious whether they are making progress in their course. 

There are lots of other formats, which all riff off this theme. See the [Wikipedia User-story entry](https://en.wikipedia.org/wiki/User_story#Creating_user_stories).

## A job to be done follows this format: 

<div class="well"><strong>When</strong> [...]
<strong>I want to</strong> [...]
<strong>So that</strong> [...].</div>

For example: **When** my class finishes a test, **I want to** compute an average of a pupil's test scores for pupils in my class **so that** it is obvious whether they are making progress in their course. 

## Other ways to communicate 

There are also other tools which people use to communicate requirements, such as [use cases and traditional requirements](https://www.scrumalliance.org/community/articles/2010/april/new-to-user-stories). I include this here for contrast. 

# When to use what

The user story puts emphasis on the *who?*, the job story on the *when?* (or *under which circumstances?* or *how often?*). 

It can be useful to emphasise the <em>who</em> if for example you are trying to balance competing needs across different users of the system. 

> "All of our features cater to the managers, but we haven't built anything for the workers, so there isn't actually any data coming in for the managers to see."

It can also be useful to emphasise the <em>who</em> if you have a complicated permissions system (though permissions matrices may do this better). Another case may be where a workflow which relies on several actors to complete (though maybe you should combine it with some diagrams to ensure conprehension). 

It can be useful to emphasise the <em>when</em> if you are trying to work out the intensity of a pain point (e.g. this thing is something this person has to do every day), or whether the pain point depends on something else. More pros in <a href = "https://jtbd.info/replacing-the-user-story-with-the-job-story-af7cdee10c27">this article</a>.

## Here's a radical idea: get the best out of both... 

This is my slight hack to extract the value out of both of the formats. This takes place at ticket level: 

* Include information on user type, preferably in a way where you can sort by user type e.g. keywords in titles if you have text search, or a label if your project management tool works better with that. 
* Write stories inspired by jobs to be done to convey the situational context.
* Add as many other things as is needed to best convey the intention of the ticket, diagrams, permissions matrices... go wild!

![](http://techtohuman.s3.amazonaws.com/images/WL%202017-04-30%2015%2043%2047.png)

As you can see, we now have both people and time information included. The benefits of this approach are being to ask yourself questions such as: 

* We have a lot of stories about User Type 1, are they the most important group to us or do we need to understand the other users better? (Note: number of stories isn't always a signifier of the relative importance of different types of user, but I find this a useful quick check for bald bits and blind spots.)
* The types of problem faced by User 3 seem to be more regularly occurring than those of User 2, might they be a good place to start?
* The problems of User 2 seem to depend quite heavily on the processes described for User 3 (e.g. getting data into the system) should we put those first?

## Summary 

![](http://techtohuman.s3.amazonaws.com/images/Productivity-methods.jpg)
<small> Image credits: <a href="https://blog.todoist.com/2015/11/30/ultimate-guide-personal-productivity-methods/">todoist</a>.

No template is rigid. Always look for the intention captured by a template and hack it until it does what you need. 

You will probably find different ones useful in different scenarios! 






