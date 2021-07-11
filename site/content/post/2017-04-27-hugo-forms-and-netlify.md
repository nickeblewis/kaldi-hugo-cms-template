---
title: Integrating Netlify Forms
date: 2017-04-27T19:07:44.240Z
description: >-
  Recently we added two forms to HeadForCode. Learn how to do this in your
  static generated website and how to utilise Netlify's form and notification
  features. I am sure you will agree that they are awesome!
image: null
---

Recently we needed to add both a newsletter sign up and contact form to this site. This site is powered by Hugo and hosted on Netlify, so we decided to use their own forms features. The clever thing is that you can integrate any form with email, slack and Github integrations amongst one or two other things. You can also call external web hooks, so we shall investigate those in a later post to consider the myriad of options that could open up for us. Powerful stuff.

This tutorial isn't restricted to just Hugo powered websites, we know it works with sites built in React and all manner of other ways. So long as you can edit your own HTML forms, you are good to go. 

## Setup your form's code

1. Add the **netlify** attribute to your **form** tag
2. Then make sure your **input** tags have their own **name** attribute that identifies each field. The name is used to identify the field once the form capture is sent off.
3. Make sure that you assign a **name** attribute to your **form** tag too, especially if you plan to add multiple forms to your site, you'll need to be able to distinguish between them later.
