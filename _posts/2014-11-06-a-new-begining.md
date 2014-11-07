---
layout: post
title: A new beginning
tags:
 - drupal
 - jekyll
---
So my website is no longer on Drupal. Shocker.

I still think Drupal is great, And work with it daily, but for a personal site which doesn't get much in the way of attention it was too much to have a great big CMS to maintain. The recent Drupal security bugs clinched it. I decided to try something new. Jekyll. 

No php files with security risks. Just plain old HTML. I couldn't quite part with my hosting, and liked the idea of plugins so I didn't go with github pages. But I did like the idea of push to deploy. 

So my trusty Raspberry-Pi came to the rescue. With a nifty little build process:

  * I git push to a repo on my pi
  * Pi builds the site
  * Pi ftps the site to my host
  * Pi purges cloudflare

In theory it should be fast and smooth. So more blogging. We will see...
