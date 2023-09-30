---
title: Spaceship Escape
date: 2013-01-25
categories: [Project, GameMaker]
tags: [gamemaker, video game, demo, arcade, fake obstacles]
image: /assets/img-preview/gm-13.jpg
gm-game-idx: 13
---

Starting to find my game on arcade style game.
Control an adventurous spaceship seeking for treasures on a mysterious cave.

> The original version did not include touch control nor the "fire" button on the top right.
This have been added to be possible to play the game on a mobile
{: .prompt-info }

{% include gm-details.html width=400 height=288 %}


Although it's simplicity, there is actually a lot of complexity in this game which started
to use more advanced programming concepts.

From a game design point of view, I had this idea of different cave section chosen randomly with a 
same start/ending for a smooth transition.
There is a total of 10 different caves (with one unfinished and unused) chosen randomly.

Another system that I was pretty proud of is the mechanic to calculate the distance travelled.
Basically there is a hidden vertical bar that follow the spaceship vertically and move backward
whenever the spaceship touch it which increase the distance.
{% comment %}TODO: add a gif of the distance mechanic {% endcomment %}

{% comment %}TODO: write regarding hidden blocks (same idea as Smiley Adventure) {% endcomment %}
