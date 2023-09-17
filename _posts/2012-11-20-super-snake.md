---
title: Super Snake
date: 2012-11-20
categories: [Project, GameMaker]
tags: [gamemaker, video game, demo, arcade, snake]
image: /assets/img-preview/gm-12.jpg
gm-game-idx: 12
---

My improved version of the Snake game.
Eat the different fruits and avoid the walls and your tail.

{% include gm-details.html %}

The gameplay is a classical [Snake](https://en.wikipedia.org/wiki/Snake_(video_game_genre)) game.
The goal of the game is to get the highest score, but the "longest tail" is also stored (but only the best value)

The different fruits that you can eat grant different amount of points and don't last the same time:
 - Banana: 10 points (last 18 seconds)
 - Apple: 20 points (last 16 seconds)
 - Grapes: 30 points (last 15 seconds)
 - Watermelon: 50 points (last 13 seconds)
 - Melon: 80 points (last 12 seconds)

There is also different bonuses:
 - Coin: Grant 150 points
 - Star: Grant invincibility for a few seconds
 - Scissors: Reduce the snake tail size of 3 (if the size is higher or equal to 5)
 - Missile: Give one more missile


We are getting closer to a "finished game". There is even a menu with options!
This options allows you various things like changing the color of the snake (with a rainbow version),
choose if you want to warp on the screen or not
and the initial of missiles.
Although the dialog will prevent you to put more than 10 missiles, there is actually an easter-egg which
allow you to set the value `666`.

Another graphic detail in the different menus that you might have missed is the "lights rays" which slowly turn. 
It's very smooth but give a bit of style and "life" to the project.

The fruits pictures are taken from (Yoshi's Story)[https://yoshi.fandom.com/wiki/Favorite_fruit].
The score that they give is just arbitrary.

