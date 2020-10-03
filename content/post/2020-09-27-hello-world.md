---
title: Hello World 
author: Sayantan Roy
date: '2020-09-27'
slug: hello-world
categories: []
tags: Machine Learning
subtitle: ''
summary: ''
authors: [Sayantan Roy]
lastmod: '2020-09-27T02:19:24-03:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---
I  started with Machine Learning (if you can call it that ) by implementing some python code that I had found in a blog post about linear regression in my Jupyter notebook. In the first few days I tried implementing those algorithms one after the other. Things did not seem to be that hard and I thought to myself: Aha! I can do machine learning as well. Well things did not turn out to be that simple . I decided to check out some papers on ML and well:

{{< figure library="true" src="spud.gif" title="Spud!" >}}


Math and Math and more math . I did have some idea regarding Optimization techniques and Linear Algebra but not really at the level required to read the papers on ML. I had two choices: Do what I was doing i.e. have some rudimentary knowledge of ML and implement them without really understanding at a fundamental level what these algorithms were about or dig deep into the mathematics and try to understand what these algorithms really represented. Fortunately, I already had some knowledge of Linear Algebra and Multivariate Calculus. In these series of blog posts, I shall try to share with you some of the concepts I have learnt and shall be learning. (I hope some people read it 😊) I hope to learn from you guys as well.

So, let’s get started:

{{< figure library="true" src="pillars_ml.png" title="Pillars of Machine Learning" >}}

The four pillars of machine learning  are built on the foundation of solid Mathematics.

1.Linear Algebra:

2.Probablity Theory

3.Good old Calculus.

You may have seen the following equation. Even if you have not do not worry.

$$Y=X\beta+u$$
This is actually our  regression model. You may or may not have seen the following expression

$$\beta=(X^TX)^{-1}X^TY$$
This is the matrix representation of ‘estimate’ of ‘β’.

 We use calculus and techniques of linear algebra to arrive at this solution. We are going to learn what vectors are ,what matrices are ,and how to derive the above estimate of β. I hope to take you through an enjoyable ride.


