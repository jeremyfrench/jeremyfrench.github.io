---
layout: post
title: Optimize This
tags:
 - jekyll
 - github pages 
---
Getting a workflow set up to blog seems to take enough time that I tend to do the meta work and stop actually posting things.

I've moved over to GitHub pages, which may make things easier. With that and Proton Mail, I don't have any hosted services any more, I'm not sure how I feel about that.

Anyway before I posted anything I wasn't happy about the lighthouse score, so I played, and played some more. Ruthlessly stripping out bits that were not needed and doing things you wouldn't ever do on a production website. 

For most pages (other than those with external resources) I've inlined everything. Even the favicon. So only one request is needed. I've dumped analytics so there is no need to have any JS, or a cookie banner. With Gzip the whole page is about 4KB. OK it's a very minimal look and a static site, but in a world of Megabytes of JS downloading just to get a spinner for the cookie banner I quite like it. 

I know if you have a bigger site, you don't inline things so subsequent requests are lighter. But this is a personal site so I can play a bit looser with the rules. 

After doing all of that the only thing holding me back from a 100% Lighthouse score was a contrast issue, so I've fixed that too. It's probably the only time I'll see green across the board on a lighthouse test. 

It's nice to be able to experiment with things on a website which isn't mission critical, and I has kept me amused.

And you never know it may be the kick I need to start blogging more. 
