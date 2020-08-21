---
title: "Miz Jam 1 - Devlog #1"
subtitle: "Participating in my first game jam" 
date: 2020-08-17
tags: ["miz-jam-1", "game-dev", ]
draft: false
---

I was browsing the internet when I stumbled across people working on projects for a so called game jam.

{{< admonition type=info title="What is a game jam?" open=false >}}
A game jam is a competition where you try to make a game in a limited time, often under certain restrictions. It is a way to practice developing and delivering a game in a short amount of time. Check out [Indie Game Jams](http://www.indiegamejams.com/) for a list of all the jams taking place.
{{< /admonition >}}

I have never participated in a game jam myself but having seen other participate it sure sounds like a fun way to push yourself. The game jam people were working on is called [Miz Jam 1](https://itch.io/jam/miz-jam-1) and in summary it has the following rules. 

* Develop a game in **48 hours**. The development time can however be spread out over multiple days. The game jam lasts between Friday August 14th 8pm MST to Sunday August 23rd 8pm MST
* For the art and graphics in the game you must use [Kenney's Bit Pack](https://kenney.nl/assets/bit-pack)

Even though I missed the start of the game jam the kind time rules plays in my favour. Inspired by having completed my [BONK game](/post/2020-08-15-first-game-released-bonk/), I decided to join. Below I will briefly describe how far I have come after having spent about six hours thinking, prototyping and developing.

## Development

The first thing I did was take a look at the Kenney's art pack to see what I had to work with. Below is over 1000 different smaller 16x16 images stitched together into a larger one. Quite a lot of variety, from trees, building, monsters, weapons... and they can be combined in even more ways.


![Spritesheet](/uploads/miz-game-jam/colored_packed.png)

Another important consideration is the complexity of the game. 48 hours is not a lot of time and it is easy to underestimate the time required. Creating a game involves: visuals, audio, progression, story and more which you as a developer has to combine into a enjoyable experience. 

### First idea - Runaway cart?
After lunch I came back with my first idea. A cart at full speed unable to stop is traveling along a track that dead ends... Your mission was to continue laying tracks so the cart could continue traveling without crashing. Make it difficult by having obstacles appear and there being a limited number of tracks you as a player could lay down. 

I started prototyping this idea by creating a project using the Godot game engine. I got a cart moving in different at the press of the arrows keys. Around this time though I hit a mental road block, and I was unsure how to continue. I took a look at the sprite sheet again.

### Second idea - A flying tree!
Then a brilliant idea hit me! Combine the tree sprites, turn them 90 degrees and add a dude on top and you got a *tree surfer*. I could repurpose much of the the movement from the previous prototype along with added diagonal movement, and after having set up the graphics in Godot I had a moving flying tree. Then I added a water tank to the tree and implemented a shoot mechanic to be able to launch both the leaves and the water. The results is the following beauty:

![Game prototype 1](/uploads/miz-game-jam/day-1.gif)

You might say it does not make any sense and you would be right. I'm secretly laughing at what i have made, but I'm sticking with it. As I start to build the world around this it might make a bit more sense but at the same time the fun part of game development is the freedom you have to be creative. Creating these imaginative worlds!

Then I set up the framework for a main menu with a play button, and started on a custom theme for the interface, though not much to show there. I also started looking into *tile maps* as a way to place images in a grid to create a world easily from the images in the art pack. I watched the video [Using the Tileset Editor in Godot 3.1 (tutorial)](https://www.youtube.com/watch?v=V9OoaOlXc_4&) to get up to speed on how it is used. 

Anyways, so yeah, a guy that is surfing a tree that can shoot leaves and water! What more can you want? Let's see where this leads...  :evergreen_tree:

To be continued!