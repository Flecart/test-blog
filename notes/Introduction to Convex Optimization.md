---
layout: page
permalink: notes/introduction-to-convex-optimization
tags: en
title: Introduction to Convex Optimization
---

#### A brief history

This field was quite developed in 1970 (started in 1920) when mathematicians had the same problem over and over again and needed a name. But this was only the theory. The practical applications came later. A modern use is in machine learning a statistics.

Form historical point of view
- 1947 simplex method popularized by Dantzig at Stanford
- Many people in soviet union in the ´60 worked on this (they already know about he applications!)
- People in aerospace engineering used these in the '60 to balance loads and stuff like that
- '90 people started using it in communications, like control and signal processing.

## Important Theorems

### Separating hyperplane theorem

Given two non-empty disjoint sets, there exists $$a \neq 0$$ such that

$$
a^{T}x \leq b, \text{ for } x \in C
$$

And

$$
a^{T}x \geq b, \text{ for } x \in D
$$

We can understand this as separating line!

### Supporting hyperplane theorem


## Dual theory

### Minimum and Minimal


### Generalized Inequalities
We now overload the operator $$\leq$$ with a new meaning used. The mean inspiration is from a proper [cone](/notes/analisi-di-convessità#convex-cone).
We say that given a cone $$K$$ the generalized inequality (partial order) is defined as this:

$$
x \leq_{K} y \iff y - x \in K
$$

Similarly the strict partial order is true when $$y - x \in int  K$$ that is, it is in the interior of the cone (no borders).

### Dual cones
We define this cones to be, given a cone $$K$$, the dual is:

$$
K^{*} = \left\{ y \mid y^{T}x \geq 0 , \text{ for all } x \in K \right\} 
$$

For definition of cones see [Analisi di Convessità#Convex Cone](/notes/analisi-di-convessità#convex-cone).
It's called **self dual** when the dual is itself (and example is the first quadrant).


### Shur complement
TODO



# References