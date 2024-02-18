---
title: Tank Tank Attack !
date: 2013-10-23
categories: [Project, GameMaker]
tags: [gamemaker, video game, multiplayer, survive]
image: /assets/img-preview/gm-17.jpg
gm-game-idx: 17
---

Local two player fighting game. Move and shoot with your tank to attack your opponent.
Different bonus will appear on the map, pick them up to ease your victory!

{% include gm-details.html %}

### Miscellaneous
#### Obstacles
Depending on the map, there is different object in the game that your tank can use as a way to defend or hide:
 - Box: Simple wood box that will be destroyed by one tank bullet
 - Brick walls: Destroy tank bullets on contact
 - Trampoline blocks: Bullet will bounce out of it
 - Trees: Hide under it
 - Dungeon: Hide inside it

#### Weapons
By default, your tank will shoot bullet that goes straight and inflict 10 damage. 
Weapons box can appear randomly on the map giving your tank a different way of shooting:
 - Waver: will shoot 2 bullets with a wave pattern
 - Canon: bullet will inflict 25 damage, but it is slightly slower and take longer to reload (0.5 seconds instead of 0.25)
 - Machine gun: allow you to let the shoot key pressed to keep shooting
 - Spazer: shoot 3 bullets, 1 straight and 2 diagonally. The bullet will last less
 - Sniper: bullet speed is increased

#### Bonus
Bonuses will randomly spawn on the map. Touch them to pick them up. You can shoot at them to destroy it.

- Health: Will give you extra health (1/4 +0, 3/8 +20, 1/4 +60, 1/8 +100)
- Shield: Protect the tank from basic damages for 8.5 seconds
- Missile: grant a powerful missile that will be used instead of the next bullet. Its explosion cause 80 damage, can destroy 
some obstacles like box, brick walls and trampolines blocks!
- Wave x3: Purple laser that will deploy itself, traversing obstacles, destroying bullets causing 30 damages


### Project ideas
This project is actually composed of several different parts which are their own-separated "game".
The idea was to merge all of them at the end to gain some development time.
This final merged never happened in practice, but the individual parts does exist.

#### Level-editor
I worked for very long for a level editor. The idea was to let the player do their own custom maps and play on it:
![level editor tank tank attack demo](/assets/gm-games/17-tank-tank-attack/other-screens/tank-tank-attack-level-editor-demo.gif)
_Demo of the level editor_

Unfortunately, the "saving the map" was too complicated for me to handle, so the idea was dropped.
But I was pretty proud of my system, in particular to determine the water tiles (even if the code is terrible).

#### Menus
A menu on the title page with different buttons
![menu](/assets/gm-games/17-tank-tank-attack/other-screens/menu.jpg)
_Menu with little animations on each icon_

##### Play
Redirect to the main game

##### Help
Redirect to an interactive help page with details on the different obstacles and bonuses
![help top](/assets/gm-games/17-tank-tank-attack/other-screens/Aide1.png)
_Top of the help screen_
![help bottom](/assets/gm-games/17-tank-tank-attack/other-screens/Aide2.png)
_Bottom of the help screen (with clickable item on the bottom to have more details)_

##### Options
Menu to change the keyboards key used for playing and other in-game options
![options](/assets/gm-games/17-tank-tank-attack/other-screens/options.jpg)
_Option page_

![options keyboard change](/assets/gm-games/17-tank-tank-attack/other-screens/change-control.jpg)
_Keyboard key choice option page_

![options parameters](/assets/gm-games/17-tank-tank-attack/other-screens/parametre.png)
_Parameter option page_
