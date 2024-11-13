---
layout: post
title: Go Dev diary #1
image:
  path: /assets/images/go.png
  height: 440
  width: 440
  alt: Gopher
tags:
 - Golang
---
# Go Dev Diary 1.

I've coded in many languages, since BASIC in the 80s I have lost count.

I try to play with a new one every couple of Years to keep me current and to understand what's new.

I'm familiarizing myself with go. A lot of the new things are interesting. Using another language that has refused to go the OO route makes me think about the good and the bad of how I use OO elsewhere.

Judicious use of Interfaces is the king for both I think. I'm not talking an identekit interface for each object, but a considered approach to what the common interfaces in your application are.

Go's duck typing lends itself to this easily, perhaps too easily as you don't need the explicit intent to implement something at source. It may also be quite easy to get out of sync with an interface on a large code base. I'm sure there are ways round this but it seems like something you'd need to watch out for. 

The other thing, is that Go's packages are a lot like a singleton. They can have their own public and private variables and functions which are unique and global across an application. 

I didn't realise this until I was benchmarking something (also for fun and to try out the benchmark test, they are neat), I realise that the regex compile was taking a lot of time and it only needed to be instated once. 

It took a little head scratching but then I realised that if I just created the variable outside of the function it would work. The function was over ten times quicker then. 

Regular expression objects are mostly thread safe so this is fine to do. Well there may be some as yet unknown drawback. But I guess that will give me something else to blog about.

I'm also wondering if there are ways to compile the regex at compile time as it will not change while the app is running. That would seem better. 

So I'm still discovering things but at least for my own sake I thought I'd jot some thoughts down.
