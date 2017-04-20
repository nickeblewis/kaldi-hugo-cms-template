---
title: 'Hugo: Installing Disqus'
date: 2017-04-20T10:37:09.708Z
description: >-
  We had a few issues installing Disqus this week, so tried it the manual way
  instead and that worked. Let me explain...
image: /img/disqus_logo_-_white_on_blue_background.png
---

We wanted to include Disqus as part of our blog post templates and at first I naturally assumed that adding:

```
{{ template "_internal/disqus.html" . }}
```

To the _single.html_ template file would do the trick? Well it did and it didn't at the same time. It would try and load the Disqus component at the appropriate spot on the page but with an error, stating that Disqus couldn't be loaded, please refer to the troubleshooting guide.

I gave up on this approach and have a feeling that the script it renders out may be either out-of-date or I am missing something?

So instead I set up a new website on Disqus an integrated the script code that provides in the templat file that caters for all blog posts. Got it working!