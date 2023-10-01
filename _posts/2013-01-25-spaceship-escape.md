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

Like most of the previous games, it focuses on having the best score. 
There is 3 different kind of collectibles for this:
 - Coin (10 points): can be anywhere in a cave section, will lead to a safe path.
It will be destroyed in contact of the spaceship laser
 - Diamond (150 points): only spawn above a cave block (with 1/16 chance)
 - Gem: found in harder to reach places in cave section. There is 6 different gems that can spawn:
   - Blue Sapphire (200 points): 50/182 chance
   - Red Ruby (250 points): 40/182 chance
   - Purple Pearl (300 points): 40/182 chance
   - Green Emerald (400 points): 30/182 chance
   - Gray Diamond (500 points): 20/182 chance
   - Multicolor Opal (1000 points): 2/182 chance

From a game design point of view, I had this idea of different cave section chosen randomly with a 
same start/ending for a smooth transition.
There is a total of 10 different caves (with one unfinished and unused) chosen randomly.

Another system that I was pretty proud of is the mechanic to calculate the distance travelled.
Basically there is a hidden vertical bar that follow the spaceship vertically and move backward
whenever the spaceship touch it which increase the distance.

![Spaceship distance system gif](/assets/gm-games/{{ gm_info.folder-name }}/img/anim-distance.gif)

Some blocks are a bit lighter, similar to [Smiley Adventure]({% post_url 2011-12-12-smiley-adventure %}) 
where touching this blocks will destroy them, here you simply go through it which can lead you to secret path with gems

I also add a complex system of "deactivation".
Some objects such as coins are deactivated when outside the camera view to avoid using too much resources.
My first step towards optimisation in my games.
