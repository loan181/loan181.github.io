---
title: Space Attack
date: 2012-07-05
categories: [Project, GameMaker]
tags: [gamemaker, video game, cancelled, demo, space]
image: /assets/img-preview/gm-7.jpg
gm-game-idx: 7
---

After once more cancelling the Zelda project, I decided to find an easier project.
I hesitated between a Pac-Man or Space Invader, as I had bad memories of Pac-Man coding in
[Smiley Adventure]({% post_url 2011-12-12-smiley-adventure %}) I decided to go with
a variant of space invader.

{% include gm-details.html %}

The game itself is pretty hard to play and not super enjoyable, 
but is well advanced compared to the previous one we saw.

Your spaceship have some health point, it will start to smoke in red when hurt then explode.

There is 3 different kind of enemies, each having different health points and behavior.
None of them moved, but 2 of them will shoot projectiles.
The first lane straight down while the last one will sometime shoot in the spaceship direction.

The blue lines on the side are actually trampoline on which the spaceship lasers can bounce.
They are placed to that it can touch the last lane if you are smart enough to figure it out!
Unfortunately, the bounce system is a bit broken, 
so your laser will likely be stuck in the trampoline or will be lost in the space forever.

If you are patient enough to kill an enemy, they will sometime drop a bonus.
They give various things like health for the spaceship, points or shield energy.
Some of them move straight down while others will move with a zigzag pattern.
In theory, it will be attracted by the spaceship if it is close enough from the bonus.
But it will likely fail as I programmed it in a poor way.
{% comment %} TODO: check the code or F1 Info to see what bonus do {% endcomment %}

If you haven't noticed in the menu, there is a "special mode" which was actually a project for a 2 Player mode.

There is a bug that I never fixed: 
while in game, press `Escape` and the spaceship will stay on screen in the menu and if you launch the game back.
You can also have 2 red spaceship if you play in 2 Player mode.

There is also left-over in the code for an extra 3rd player which was never implemented.
