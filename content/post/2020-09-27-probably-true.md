---
title: Probably true?
author: ~ 
date: '2020-09-27'
slug: probably-true
categories: []
tags: Probability Theory
subtitle: ''
summary: ''
authors: [Torsha Chakravorty]
lastmod: '2020-09-27T01:55:25-03:00'
featured: Yes
image:
  caption: ''
  focal_point: ''
  preview_only: no
projects: []
---
I came across this post somewhere I cannot recall. A man (call him Maity (a)) asks a professor, the probability of there being a bomb on the plane that he’s travelling in. A bit confused, the professor tells him, it’s a rare event. Maybe one in a million? Now Maity asks again, what would be the probability of there being two bombs on that plane?! Utterly confused, the professor replies, well, if the two events were to be independent (which is highly unlikely), it would be the square of the first probability, i.e. one in a trillion. Satisfied, Maity now always carries a bomb with him, whenever he’s flying. Just to lower the chances of the second bomb being on the plane.

If Maity’s reasoning were true, then we could reduce the chances of terrorist attacks by simply carrying bombs on planes.

Let’s begin.

We (not us personally of course, but serious people writing textbooks) define a random experiment as a process that leads to different outcomes when repeated numerous times.

Now, look at what went wrong in the situation above. Do you think Maity lowers the probability of the bomb being on that flight if he’s carrying one too? Of course he does not. Maity carrying a bomb, does not reduce the chances of a terrorist planting a bomb on the plane, since these events are statistically independent.  

Suppose a terrorist plants a bomb, same time as Maity brings his own. This does not imply that the terrorist planting the bomb was because of Maity bringing one. It would be a simple case of two independent events occurring together by chance. This is often called post hoc ergo propter hoc, or the post hoc fallacy (b). 

Any set of independent events (take two of them, A and B) satisfy:

\begin{equation}
\tag{1}
Pr(A|B) = Pr(A)
\end{equation}

The above literally translates to the following. The chances of event A happening, given that event B has already happened, is same as the chance of event A happening without considering event B at all, since these are in no way related.

Take an example.

Take A as the event of rainfall on say Dec 1, 2019 and B be the event of me performing a rain dance on 30th November. Sadly, me performing a rain dance does not increase or decrease the probability of rain occurring on Dec 1. We say that A and B are two independent events.

Speaking of events A & B, we claim the following four possibilities

*1*. Both A and B happens

*2*. Neither A nor B happens

*3*. A happens, B doesn’t

*4*. B happens, A doesn’t

For events that are statistically independent, we know

\begin{equation}
\tag{2}
Pr(A ∩ B) = Pr(A).Pr(B)
\end{equation}

Coming back to Maity. From his perspective, he thought getting a bomb on the plane would mean a lower probability of there being another bomb (Prof told him one in a trillion, can’t blame him either). Maity is assuming statistical dependence here. Whereas the idea of,

$$Pr(Terrorist\ plants\ bomb| Maity\ carries\ bomb) = Pr(Terrorist\ plants\ bomb)$$  

holds for this case.

More than confused, I personally have always found probability theory thought-provoking. How all of this, the technical jargons across disciplines converge to certain themes, certain basic problems that people are trying to solve. And it will be one step at a time, that we cover each of them. Every fancy concept out there; starting from Bayesian Techniques to Causal Inference to certain concepts in Behavioural Science (a personal area of interest) will be broken down to simple bits and pieces. While this post does not define various definitions, this is just an introduction to one of coolest topics out there. Stay tuned 🙂

(a) Maity is a friend (good-humored too, I hope), an artist and a co-author of this blog.

(b) Literally translating to, “after this, therefore because of this”.