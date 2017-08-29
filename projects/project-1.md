---
layout: project
type: project
image: images/micromouse.jpg
title: OthelloWar
permalink: projects/micromouse
date: 2016
labels:
  - Java
summary: A 2-4 player game, inspired by the rules for board game 'Othello'.
---

<div class="ui small rounded images">
  <img class="ui image" src="../images/micromouse-robot.png">
  <img class="ui image" src="../images/micromouse-robot-2.jpg">
  <img class="ui image" src="../images/micromouse.jpg">
  <img class="ui image" src="../images/micromouse-circuit.png">
</div>

Micromouse is an event where small robot “mice” solve a 16 x 16 maze.  Events are held worldwide.  The maze is made up of a 16 by 16 gird of cells, each 180 mm square with walls 50 mm high.  The mice are completely autonomous robots that must find their way from a predetermined starting position to the central area of the maze unaided.  The mouse will need to keep track of where it is, discover walls as it explores, map out the maze and detect when it has reached the center.  having reached the center, the mouse will typically perform additional searches of the maze until it has found the most optimal route from the start to the center.  Once the most optimal route has been determined, the mouse will run that route in the shortest possible time.

OthelloWar is played out on a 2-D grid with a turn-by-turn format. Each team can do four things in one turn: Create units, move/use units, move 'guard blocks', and perform a color change. When a colored block is placed on the grid, if there exists the same colored block in the same row or column, all blocks in between the two are changed to that color.

The project started off as me wondering what I could do with Dylan Kobayashi's Java E.Z graphics. I wanted to practice developing the logic of a program separate from the visuals. I started coding the logic without a solid plan, and as a result I was constantly making changes. After taking the time to think about the overall structure, I was able to develop code much more quickly. The color change mechanic was the most complex part to figure out. It involved the use of several data structures (queue and stack). After finishing the logic I started to work on the graphics. To my suprise, I ended up needing a graphics counterpart for every logic class. Trying to implement a GUI that worked primarily with the mouse took a lot more than I expected, and was one of the more difficult parts of the project. Overall there were several unexpected problems that required changes in multiple classes that could have been avoided with extensive and proper planning.

You can learn more at the [UH Micromouse Website](http://www-ee.eng.hawaii.edu/~mmouse/about.html).



