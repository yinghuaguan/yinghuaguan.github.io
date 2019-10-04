---
layout: post
title:  "AI Project Development Cycle,Part 1: Problem Definition"
image: '\assets\img\data.png'
date:   2019-10-04 10:00:00
tags:
- AI Dev
description: 'AI Development Cycle: 1. Problem Definition'
---

If you’re interested in using Machine Learning (ML) to enhance your existing product in the real world, it’s important to understand how AI development functions within the lifecycle and context of a software development project. According to [a recent survey by Gartner](https://www.gartner.com/en/newsroom/press-releases/2019-07-15-gartner-survey-reveals-leading-organizations-expect-t), industry-leading organizations have, on average, four AI
projects in their development pipelines, and this number is projected to double within the next year. Artificial Intelligence is perhaps the most transformative technology available today.

At a high level, every AI development project follows these six steps:

1) Problem definition

2) Data gathering

3) Feature definition

4) AI model construction

5) Evaluation & refinements

6) Deployment

In this article I will share the best practices for the first step: defining the problem.

The proper definition and characterization of an AI-addressable problem is often more important than the choice of algorithm itself. It can save you tons of work further downstream, preventing you from solving the wrong problem.

>It is not necessary for the pattern in data to be immediately perceivable by humans for AI to make predictions - but there does need to be a pattern.



## To AI or not to AI?  
Begin formulating your problem by asking yourself this simple - yet critically important - initial question: is there a pattern? The premise that underlies all Machine Learning disciplines is that there needs to be a pattern. If there is no pattern, then the problem cannot be solved with AI technology. It is fundamental that this question is asked before deciding to embark on an AI development journey.

Superficially, ML functions much like the human brain. The decisions we make every minute of every day are based on a lifetime of pattern recognition. When we encounter a scenario that is not identical to one that we have experienced before - say, a unique road configuration at an intersection, while driving - we are able to effortlessly deduce what the ideal response should be. This is due to a mental model that the brain has developed - and continues to develop - given a hundred thousand data points, and processed through our inherent ability to recognize patterns at a subconscious level.

ML is a mathematical approximation of this strategy, applied to the digital world.

It is not necessary for the pattern in data to be immediately perceivable by humans for AI to make predictions - but there does need to be a pattern.

![If it is believed that there is a pattern in the data, then AI development techniques may be employed.](..\assets\img\data.png)  

## What type of AI problem is it?    

If it is believed that there is a pattern in the data, then AI development techniques may be employed.

Applied uses of these techniques are typically geared towards answering five types of questions, all of which may be categorized as being within the umbrella of predictive analysis:

1) **Which category?** (Classification)

2) **How much or how many?** (Regression)

3) **Which group?** (Clustering)

4) **Is this unusual?** (Anomaly Detection)

5) **Which option should be taken?** (Recommendation)

It is important to determine *which* of these questions you’re asking, and how answering it achieves your business goals.

## Simplify your problem    
Sometimes the target metric that you would like to predict may not be directly quantifiable. For example, say you want to predict a customer’s enjoyment level during their interaction with your website. Enjoyment is hard to define and model, so we need to dig into the data to determine if there are simpler tasks that can act as good proxies. In other words: what tasks are correlated with enjoyment? Often, a good approach is to try looking for intermediate events that affect the desired final outcome — but use events that are more well-defined, and therefore easier to model. In the example of enjoyment, we might wish to use the “total time that customers spend on the website per week” as a proxy for enjoyment.  

Think carefully about what the right machine learning task for your AI development project actually is. This may seem obvious, but in reality it can be surprisingly messy. Failing to define your problem properly may cost you a huge amount of time and money.  

## Reference  
https://research.fb.com/videos/field-guide-to-machine-learning-lesson-1-problem-definition/?source=post_page-----8834823e0bbc  

https://docs.microsoft.com/en-us/azure/machine-learning/studio/data-science-for-beginners-the-5-questions-data-science-answers?source=post_page-----8834823e0bbc
