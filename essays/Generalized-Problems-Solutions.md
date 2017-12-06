---
layout: essay
type: essay
title: Generalized Problems and Solutions
date: 2017-12-5
labels:
  - Design Patterns
---

<h3>Generalizing Types of Problems</h3>

In mathematics, a professor will teach a class how to solve types of problems, rather than how to solve every example problem presented in a textbook. I do not have the product of 43 and 15 memorized. However, I know that I can break it down into smaller steps:
```

 3  x 5  = 15
 3  x 10 = 30
 40 x 5  = 200
 40 x 10 = 400

 15 + 30 + 200 + 400 = 645

```
This example problem can be generalized, and applied to all "product problems"

The product of _abc_  and _zy_ is equal to
```
<pre>
  <i>c</i>   x <i>y</i> = <i>cy</i>
  <i>c</i>   x <i>z</i> = <i>cz</i>
  <i>b0</i>  x <i>y</i> = <i>by0</i>
  <i>b0</i>  x <i>z</i> = <i>bz0</i
  <i>a00</i> x <i>y</i> = <i>az00</i
  <i>a00</i> x <i>z</i> = <i>az00</i>

  <i>cy</i> + <i>cz</i> + <i>by0</i> + <i>bz0</i> + <i>az00</i + <i>az00</i> = answer
</pre>

```

The idea of making a general solution to a reoccurring problem is not exclusive to mathematics. It is done with various sciences, engineering, and programming problems. In software development, a general solution to a type or class of problems is known as a [design pattern](https://en.wikipedia.org/wiki/Software_design_pattern).  

<h3>You are probably used one in your last project</h3>

The largest project I've worked on by myself was [OthelloWar](https://zach2heth.github.io/projects/OthelloWar), a game I made for fun. The first challenge I faced was figuring out the overall structure of the code, and how information would be passed around between Java classes. I was only absolutely sure I wanted to separate the logic from the interface.

I had unknowingly decided on a design pattern known as [Model-View-Controller (MVC)](https://en.wikipedia.org/wiki/Model%E2%80%93view%E2%80%93controller). The basic idea is to have a mediator (aka, the controller) between the logic (model), and interface (view) which passes the information between the two. It allows code to be reused as long as the API is maintained. I ended up combining the controller into the view classes, but that was my specific implementation of an overarching design pattern.

There's a very high chance that you have used a specific implementation of a design pattern in your last software project as well. Most problems require a modified version of a design pattern, or maybe even a a mixture of multiple. Calling something a design pattern is simply a way to formalize and define a common method of solving problems presented in programming.
