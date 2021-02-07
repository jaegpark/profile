---
layout: page
title: Defeat the Heat
description: game dev - java - 1 mo - 2019
img: /assets/img/dth_images/dth10.jpg
importance: 1
---

## What it does

Defeat the Heat is a three-level desktop game that teaches the player about fire safety, made in `java` for my ICS4U culminating.

We broke up the concept into three stages: learning, practicing, and application - hence the three levels.
Using keyboard and mouse to navigate the game, the end goal is to learn fire safety mechanics:
common fire hazards, different fire extinguishing equipment, and the types/applications of fire extinguishers.

<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/dth_images/dth2.jpg' | relative_url }}" alt="" title="level one"/>
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/dth_images/dth4.jpg' | relative_url }}" alt="" title="level two"/>
    </div>
</div>
<div class="caption">
    On the left, level 1 focuses on learning fire hazards. On the right, level 2 focuses on household firefighting. 
</div>
<div class="row justify-content-sm-center">
    <div class="col-sm-7 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/dth_images/dth8.jpg' | relative_url }}" alt="" title="level three"/>
    </div>
</div>
<div class="caption">
    Above, level 3 focuses on the applications of different fire extinguishers.
</div>

## How it was built

My partner and I used the `java.awt` and `java.swing` libraries to create the GUI interfaces. All the code was written in `java`, using *object oriented programming techniques*.
The transition graphics (menu, navigation, popups) were hand-done. We used MS Paint.

For the final level, I used 2D map editors to make a maze. I used Piskel to draw the animated sprite.

You can check out the full project code [here](https://github.com/thejammerr/Defeat-The-Heat){:target="_blank"} on my Github.

## Challenges

Initially we divided the work like so:

Rohan:
- Levels One and Two.
- Graphics for those respective levels.

Jae (myself):
- Level Three (maze).
- Main menu navigation and graphics.
- Putting the game together, including intricacies like the pause menu.

That last step was often problematic. Because we discussed the project very loosely, we used different classes in our GUI,
so some things did not appear when we merged our code. We had to rewrite quite a bit of it.

## Takeaways

1. Make sure to define the class hierarchy structure before splitting groupwork.
2. Use case-sensitive path directory strings in image paths. The .jar will not find these images (.png vs .PNG), but the IDE will compile and find the images perfectly fine. Basically, don't trust the IDE.
3. Use newer libraries! Something that I regret is not using more practical libraries that existed. This would've made our interfaces and popups more modern, and look less archaic. 
4. Invest time into graphics. My partner and I didn't really care too much about aesthetics (hence takeaway 3.) and cared more about functionality. This made our game look crappy, even though it still worked as a game.
Since game dev is something where user interactivity is important, I'll be sure to put more care into making an aesthetic game next time. 