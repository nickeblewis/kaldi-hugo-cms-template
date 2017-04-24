---
title: Hugo and us
type: Post
date: 2017-04-21T10:37:09.708Z
author: Nick Lewis
---

_Todo: add screencast here when I get time_

__TL;DR__

We have switched to using Hugo from Phenomic, still hosting on Netlify and we have added their new app called Netlify CMS which is very clever and warrants an entire article or screencast of it's own. It is simple but very powerful. I mean that this way of building sites has up until now been very techie, not at all good for people who are not of a technical mindset, such as Rolf, however I think this setup will actually be a lot nicer to use, even when compared to Wordpress.

In any case, I need to had this over to you, so that you can learn it and pretty much take over on the running of future sites, such as Carpnado. Incidentally we plan to catch up with them in May.

So here is a little bit of documentation on how to get up and running, plus some other ideas that have popped into my head

## Hugo?

Hugo is a static site generator and there are many that we could have chosen in it's place. We were using Phenomic for example which I found works very well but we are likely to hit thousands of pages as this site grows. The guys at Smashing Magazine for example switched to Hugo and so have other big online publishers..... why? Hugo is very fast in how it processes pages. There are many other benefits though that I have listed out here:

* We write our content using markdown and that is great because Phenomic does too, we can copy our content over very easily - win!
* Hugo runs on Mac, PC and Linux
* Works with Netlify whom we've been using for awhile now
* Oh so many other things, we will come across as we go along that are cool

## The Github repository

Github as a back-end is an exciting prospect and to be honest this [article explains it better than I can](https://snipcart.com/blog/netlify-cms-react-git-workflow?utm_source=Snipcart+email+subscribers&utm_campaign=486fda4eb8-mc-snip-march17-content-netlifycms&utm_medium=email&utm_term=0_3e16e05ea2-486fda4eb8-122819253), so go and have a [read](https://snipcart.com/blog/netlify-cms-react-git-workflow?utm_source=Snipcart+email+subscribers&utm_campaign=486fda4eb8-mc-snip-march17-content-netlifycms&utm_medium=email&utm_term=0_3e16e05ea2-486fda4eb8-122819253) of that!

## The Netlify account

## Netlify CMS - Introduction

### Access and login

I will need to add you as a collaborator to the Kaldi project and once I've done that, you will be able to go to [www.headforcode.com/admin](http://www.headforcode.com/admin) and login.

## Netlify CMS - Editorial Worflow

## Thoughts on branching

Apart from the mandatory Master branch, I am proposing we set up the following to start off with:

* Dan
* Nick
* Courses - this aspect of the site isn't ready yet, so my thoughts are to hide the changes on the master branch and develop them under their own branch. YOu know already that we can switch between branches almost as if they are separate sites. Once happy we then merge them together and that in turn triggers a new build on the live server.
* Services
* About
* Blog
* Contact

## Deploying changes to live site

## How does Hugo work