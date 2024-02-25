---
title: Shape Dodge
date: 2013-11-17
categories: [Project, GameMaker]
tags: [gamemaker, video game, skill, survive]
image: /assets/img-preview/gm-18.jpg
gm-game-idx: 18
---

Embark on a thrilling geometric skill-survival adventure!
Take control of a resilient rounded square player on a rectangle filled with perilous obstacles of 
various shapes with various movement patterns. 
Your mission is to survive the relentless challenges, dodging, and weaving to avoid contact with these hazardous elements. 
The stakes are high, as your health dwindles with each encounter.
Dive into the action, conquer the geometric chaos, and emerge as the ultimate rounded square champion!

{% include gm-details.html %}

The neon inspiration come from this style which was popular in Happy Wheels that I even used in my custom levels.


### Waves
The game is composed of successive waves on which various shapes with a given pattern will harm the player.
Each wave last a different amount of time and will smoothly switch to another one randomly.

#### Wave: Balls

Default wave when the game started, balls shape will randomly appear from the left moving to the right and bounce.
Deal 1 damage per frame in contact with the player.

#### Wave: Lasers

Laser beam falling from the top and disappear in contact with the ground
Deal 0.05 damage per frame in contact with one laser beam

#### Wave: Blocks

Blocks will fall from the sky staying on the ground and can stack on each other.
They do not harm the player directly, but they can crush him which will instantly finish the game

#### Wave: Rain

Little droplets will fall from the sky in random directions.
Each droplet deal 10 damage

#### Wave: Spiral / Dark hole

Spiral moving spike shapes will move back and forth horizontally in the game
Deal 2 damage per frame in contact with the spike

#### Wave: Shuriken

Shurikens will move horizontally hitting the player on contact.
Deal 20 damage per shuriken hit

#### Wave: Zone

Circle growing zone will appear randomly in the screen then disappear.
Deal 0.5 damage per frame in one zone

#### Wave: Missiles

Missiles will appear on the side and top provoking explosions on contact with anything else.
While they are quicker than shurikens, a warning sign appear on the side where it will appear. 
Deal 30 damage per missile (the explosion itself does not hurt)

#### Wave: Pushers

Horizontal moving blocks that will push the player outside the map.
It can also finish the game if the player is between 2 pushers of opposite directions 

#### Wave: Boss (unfinished)

A boss was originally planned. A big circle shape with a face that have different emotions depending on the player actions.
This boss would have randomly shoot raining projectiles and would have move in a horizontal pattern.
My first idea was to give the player a weapon to attack the boss and give a score bonus once killed.
