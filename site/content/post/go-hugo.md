---
aliases:
  - /2017/04/go-hugo
categories:
  - Development
  - CMS
  - Journal
date: 2017-04-18T14:04:10.000Z
draft: true
tags:
  - SSG
title: Go go Hugo
description: >-
  We make a big jump and move our site across to a new static site generator but
  what is all the fuss about?
image: /img/illustrations/iStock-625309490.jpg
type: Post
---

I think the time has come for something new, not just a new HeadForCode website but a whole new revolution in building sites like this because I grew tired of Wordpress. Don't get me wrong Wordpress has been great and I still use it for my personal site [nicklewis.net](http://www.nicklewis.net) but for how much longer, I am not certain.

## Hugo the SSG

There are many resources out there on what an SSG (Static Site Generator) is, so I shall not go overboard in explaining what they are. However some of the key benefits of maintaining a site that will be content heavy, will be:

* Excellent security
* Version control of content
* Ease of deployment
* No need for a cumbersome admin back-end
* You can edit code either in your favourite editor or use NetlifyCMS

## Our workflow

We are highly dependable on Git to control our workflow as well as keeping versions of all of our changes over the course of time. It also make it possible for othe collaborators to make their mark on the site too. It is really hard for any of us to mess up someone else's work, Git is our ally.

### Branching - Editorial flow

The "Master" branch should never be edited directly, since we push our changes to master in order to deploy them to the live environment, essentially no different to publishing them. So we tend to use branches and in order to apply the changes to the live site, we merge them.

### Pushing - Publish the site changes

Having merged changes to master this triggers a push action and tyhe live site updates once the deployment is complete. This is what is called continuous deployment and it makes things smooth and easy for us.

Edited in the CMS UI