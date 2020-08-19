---
title: "Miz Jam 1 - Devlog #2"
subtitle: "Flying tree -> standing tree" 
date: 2020-08-18
tags: ["miz-jam-1", "game-dev", ]
draft: false
---

Today I have spent some more hours continuing on the work from the [last devlog](/post/2020-08-17-miz-jam-1-devlog-1/). For a summary I'll list some points below:

* Added the ability to land and launch the flying tree. The state is controlled by a simple state machine. For example it contains the states: *flying* or *landed* which both has unique logic that get executed.
* Added a new player character that can jump out of the ship and walk around in the 2D world, as well as jump. It uses a fairly simple platformer controller for the movement.
* First draft of a splash screen which is supposed to get shown when first launching the game. 
* Played around with Tile maps and how to control them during runtime through code
* Set up a board to track the progress I make using notion.so (should probably have made it before... but better late than never)
* Pause menu 

Entering and exiting the tree ship can be seen in the following GIF.  
![Game prototype 1](/uploads/miz-game-jam/day-2.gif)
At the press of a button the tree lands (read slams into) on the ground and out pops the little guy. Similarly it is easy for the guy to enter the tree and take off at the press of a button. It took some hours to get it working nicely together but I think it turned out great and it feels really responsive. 

### Why have two ways of control?
As seen from the GIF above there are now two ways of control: from the tree ship and just walking around on the ground. The main reasons why I added the second way are
* Expand the core mechanics to allow for a more versatile play style. Introducing **Air** vs. **Ground**
* Have a tree that lands upright just seemed really cool
* Have a reason to add a little guy that sits onboard the tree ship

With **Air** and **Ground** separated we can make certain actions only available while flying the tree ship and others only while on the ground. As a start I made the refilling of the water tank on the tree only happen while the tree is landed. Because I plan to use this as some kind of ammunition this forces the player to land eventually to refill. I plan to add actions that the little guy can only do while running around on the ground as well.

### What is the purpose of the game? 
What I have in mind is that you have to protect your kingdom of trees against a wild wildfire that has started and that is spreading rapidly towards you. That is why I added the water tank to the tree because one mechanic will be be to put out the fire with the water. Also being able to plant more trees to help you in your fight against the fire would be cool.

Having spent almost 15 hours developing leaves 33 hours remaining to complete the game. Tomorrow I hope I can get most of the main game loop done, with added enemy fires that you can put out.  :fire: <= don't worry I put this fire on a fire resistant paper... 

Take care, and I'll update on my progress tomorrow!