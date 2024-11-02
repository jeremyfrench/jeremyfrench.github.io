---
layout: post
title: Is AI really being held up by a lack of GPUs
image:
  path: /assets/images/ia.png
  height: 440
  width: 439
  alt: Master Control Program
tags:
 - AI
---
Open AI seems to be struggling to deliver on some of it's promises. This may not come as a surprise to many.

> All of these models have gotten quite complex, We also face a lot of limitations and hard decisions about we allocated our compute towards many great ideas.

_Sam Altman as reported by [MSN](https://www.msn.com/en-us/news/technology/openai-ceo-sam-altman-says-lack-of-compute-capacity-is-delaying-the-company-s-products/ar-AA1ti41m)_

Which roughly translated means

> More power

_[Tool time Tim](https://homeimprovement.fandom.com/wiki/Tim_Taylor)_

I'm not sure this is a good idea all around. As Tim found out, often painfully, "more power" is not often the correct solution.

Now I am probably an AI maximalist, I think if AGI can be made it should be. But at the same time I don't think the current approach is going down a good path to achieve that. 

A long time ago, I was playing around with [Genetic Algorithms](https://en.wikipedia.org/wiki/Genetic_algorithm) they are kind of a cousin to some of the ML things we see today. (Unfortunately they were not part of my coursework which I probably should have been focusing on). 

I had made a virtual cat and mouse game, the cat and the mouse had a limited set of instructions which could mutate to evolve better at catching the mouse or escaping the cat. I was hoping that they would evolved to react to the environment, there was the capability to do so baked into the simulation. After an our on my mighty 486 I could see that this wasn't happening, they were just evolving to find the shortest path (which in retrospect is still quite clever but wasn't what I was looking for). I tweaked the parameters and would leave the computer running overnight, hoping that the model would show some signs of adapting. It never did.

No amount of power would change the fact that in this model, any time spent reacting to the environment was evolutionary wastage. I got bored in the end and if I remember correctly started to make a game about bees.

But the lesson has stuck with me. Sometimes a fundamental change is needed rather than throwing more and more CPU time at a problem. 

What you need to consider is what type of curve you are on, are you linear, exponential or logarithmic. In short will doubling your effort, double your payoff, make it many times better or hardly make a difference. 

My hunch is that there is a big difference in what the expectation is vs what the reality is for these new 'more powerful' models. Making the model bigger, won't stop hallucinations or enable it to reason. That will need to be some shift in how the models work, which does not mean it will be bigger or more expensive. Just better. Basic logic and calculations are trivial for a computer, using a language model to do them is exceptionally wasteful. 

There may be many market driven reasons for saying that more power is needed before Open AIs products improve, I guess we will have to wait and see what the reality is.

But don't just take my word for it:

 * <https://www.technologyreview.com/2024/10/01/1104744/why-bigger-is-not-always-better-in-ai/>
 * <https://towardsdatascience.com/survival-of-the-fittest-compact-generative-ai-models-are-the-future-for-cost-effective-ai-at-scale-6bbdc138f618>
 * <https://www.ft.com/content/359a5a31-1ab9-41ea-83aa-5b27d9b24ef9>
 * <https://news.microsoft.com/source/features/ai/the-phi-3-small-language-models-with-big-potential/>
 * <https://techcrunch.com/2024/06/11/why-apple-is-taking-a-small-model-approach-to-generative-ai/>


