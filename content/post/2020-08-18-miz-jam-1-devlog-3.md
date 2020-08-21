---
title: "Miz Jam 1 - Devlog #3"
subtitle: "" 
date: 2020-08-21
tags: ["miz-jam-1", "game-dev", ]
draft: false
---

It has been a couple of days since I last made an update on my game for the Miz Jam 1. I have been hard at work and many things have changed. There is a bit to cover so lets get started. 

#### Shiny changes
* Added trees
* Added little fires. Their behavior is controlled by a state machine, which briefly contains the following logic. 
    * Wander state - walk around looking for trees
    * Chase state - if a tree is seen by the fire it will move towards it
    * Burn state - if the fire has a tree as a target and is close enough it will start to burn the tree down  
* Fire spawners that can create more little fires
they have a few and if they detect a tree they will enter a burn state where they light the tree on fire
* Player character
    * Player now carries a stick like weapon that can be used to attack the fires and extinguish burning trees.
    * The player can burn by getting close to the fires. If enough burning has ticked up the player "dies" and gets teleported back to the tree ship. Standing next to healthy trees removes fire.
* Player tree ship
    * Can shoot bullets that creates new trees
* Tutorial text that appears when the player is close
* Sound effects and music added

The result of all these changes is shown in below:
{{< rawhtml >}}
<br>
{{< /rawhtml >}}
![Game prototype day 5](/uploads/miz-game-jam/day-5.gif)
{{< rawhtml >}}
<br>
{{< /rawhtml >}}

#### The bucket of to-dos
* Finalize the art style
* Create the world
    * Introduction/tutorial section where the controls and key mechanics are explained
    * Areas of fires that the player has to defeat to push back the spread of fire
* Enemy variation
* Integrate a little bit of story into the game
* Test, test, test!
* Submit


So how much time do I have left? About 11 hours left of the 48 hours. There is quite a bit that I would like to get done, and I do believe most of the systems are built already so I can focus now on building the levels. However, 11 hours is not a lot and I will have to prioritize what is most important. Bottom line, I should have **completed a game that is playable**, even if it is short. I'll keep up the work till I am satisfied. Thanks for reading!

