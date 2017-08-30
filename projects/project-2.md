---
layout: project
type: project
image: images/A-Star.png
title: A-Star Puzzle Solver
permalink: projects/vacay
date: 2017
labels:
  - LISP
summary: A responsive web application for travel planning that my team developed in ICS 415.
---

<img class="ui medium right floated rounded image" src="../images/vacay-home-page.png">
 
This is a LISP assignment for an AI class, ICS 361. 

The goal was to create a function, based on the A-Star algorithm, that can find a solution path to any problem that can be represented in LISP. The solution path is the steps taken, in order, to go from the start state to the designated goal state. 
The three problems given were the [river crossing](http://www.mathcats.com/explore/river/crossing.html), [water jug](http://www.math.tamu.edu/~dallen/hollywood/diehard/diehard.htm), and [8-puzzle](http://www.d.umn.edu/~jrichar4/8puz.html).

The problems were represented in LISP by creating functions that represent the different moves a player can make. They alter the current state of the puzzle. After trying out every possible move on the current state, a heuristic function creates a value that is assigned to each newly created state. A lower heuristic means the state is closer to the goal. A-Star stores all the newly created states and sorts them into a priority queue, where the lower heuristics are first. A-Star then takes the first state off of the priority queue and begins the process again. 

Doing this assignment taught me the basics of problem solving with artificial intelligence. It was my third time coding in LISP, and gave me a lot of experience with it. The same assignment was done with Depth-First and Breadth-First strategies. In the source code you'll fine file names with an 'H' at the end, meaning 'heuristic.' Those files accompany the A-Star algorithm. 
 
Source code [here](https://github.com/zach2heth/AStar/).
