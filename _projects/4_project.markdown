---
layout: page
title: Simon Says
description: game dev - turing - 2 wk - 2018
img: /assets/img/simon_pics/ss1.jpg
importance: 5
---

## What it does

As the title - this program replicates the Simon Says memory game. As the user progresses through the game, the colour flashes faster and for longer sequences.

Here's some gameplay snapshots:
<div class="row">
    <div class="col-sm-6 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/simon_pics/ss3.jpg' | relative_url }}" alt="" title="your turn"/>
    </div>
    <div class="col-sm-6 mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/simon_pics/ss4.jpg' | relative_url }}" alt="" title="game over"/>
    </div>
</div>
<div class="caption">
    On the left, the game prompts the user to repeat the flashed pattern on screen. On the right, the user repeated the wrong order, and the game is over. 
</div>


## How it was built

This project was done as my culminating for my ICS2O course, and based on what I learned, I put the entire game code in one giant .t file. 

I worked on this independently for about 2 weeks, and incorporated game audio using multithreading in the game loop. I used Mario music :)

Check out the full project code [here](https://github.com/thejammerr/Simon-Says){:target="_blank"} on my Github.

## Challenges

Since the simon says game is actually structured like a circular ring, it was hard to implement mouse coordinate checks to see which colour the user clicked on during the game.

To get around this, I essentially did many mouse coordinate checks with smaller rectangles to cover as much area in the circle as possible. 