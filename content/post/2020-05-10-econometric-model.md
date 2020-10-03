---
title: Econometric Model
author: Sayan Maity
date: '2020-05-10'
slug: econometric-model
categories: []
tags: Econometrics
subtitle: ''
summary: ''
authors: [Sayan Maity]
lastmod: '2020-05-10T04:16:56-03:00'
featured: no
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---
In the field of data analysis, we often use regression models, especially linear regression to verify any hypothesis that we made about the data. Regression models uses different mathematical and statistical tools to analyze the data, find if there exist any pattern in the data, and some-times predicts from that data. Almost everyone, from business to science, use some form of data analysis to understand and analyze the problem in hand. In sciences we always see the usage of “curve fitting” to test any assumption from existing theory.

In the case of economic sciences, the usage of data analysis has a special name. As a matter of fact, we call it “*Econometrics*” mainly to sperate our selves for natural sciences. But is that so easy? Let us search a bit…...

The word “*Econometrics*” means “*the measurement in economics*”  But this definition is too simple to digest. This definition is not complete either. Everything in economics is some sort of measurement. So, what is exactly “*Econometrics*”? 

In plain and simple words econometrics is data analysis for economics but with a catch. Unlike natural sciences we not only use it to test theory and predict but also build models. So next time someone says “*whatever, it’s just same curve fitting*” – no its not; we build theory with this! It means a lot to us.

Now, someone can ask we always used to build models (without even mathematical expression! We are artist!) so why do we need econometrics to build models? To understand this, we need to understand the difference between econometric models and economic model.

Now what is a model? Model is nothing but a simple but realistic representation of real-world phenomenon. We always prefer simple models over complex one because they are easier to understand. We assume something about the real world and based on those assumptions we build our models. With simple models there is always a fear of – either over-simplification of assumptions or making unrealistic assumption. Let us have an example- 

Say we want to measure the demand for monster energy drinks (not sponsored). We may start with assumption that demand of monster energy depends on the price of monster energy. Now based on this assumption we can write a model- If we denote demand for monster energy as D and Price of monster energy as P then we can write – 

$$D = f(p)$$

Now we have a model. But one can say this model is oversimplified and unrealistic. Price of monster energy seldom changes and demand changes from age group. So, may be, we can include age and something else. That makes the model more complete.

Now we know what a model is. So, what is an economic model? Economic model is those set of assumptions that simplifies an economic behaviour. Say if we can write the above relation more clearly

$$D = a - bp$$

That is price is negatively related with the demand. So, this is an economic model. But we know there are some other factor which may also affect this demand for monsters. So, this is just an approximation. 

In econometric model we try to generalize this thing more. We include the other factors as “*disturbance*”. Such as – 

$$D=a-bP+u$$

We assume certain feature about this disturbance later. First, we have one more problem to resolve. 

While talking about models we always consider ‘*linear relation*s’ in economics. But relations can not always be linear. Say this above relation can be –

$$D=\frac{a}{p^b} $$ 

But we can always change this into a linear model – 

$$\ln p = \ln a - b\ln p$$

So, from now on when ever we consider any econometric model, we will only talk about linear model what we usually call – “*Linear Regression Model*”.

Before finishing we should have a look into that “*u*” term. As this is what separates an econometric model from an economic model. While economic models are definite econometric models are random mostly due to this “*u*” . In the next post we will discuss more about this “*u*” .