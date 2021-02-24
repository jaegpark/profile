---
layout: page
title: theatre widget
description: applet - java - 2 wk - 2018
img: /assets/img/cinema_pics/c1.jpg
importance: 4
github: https://github.com/thejammerr/Theatre-Widget
---

## What it does

This applet I built helps a user manage a 30x20 theatre seating grid. This was one of my first projects in `java` where I utilized 
user interfaces and file I/O.

It serves two functions: checking a seat's information (name of person who reserved it, availability, and cost), and purchasing tickets and saving the information in a file.

Here are some snapshots of its functionality.

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/cinema_pics/c2.jpg' | relative_url }}" alt="" title="main menu"/>
    </div>
</div>
<div class="caption">
    Above is the main menu. They can navigate to all menu options from here.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/cinema_pics/c4.jpg' | relative_url }}" alt="" title="check seat"/>
    </div>
</div>
<div class="caption">
    Above is an example of checking the seat A20. The price and availability is shown.
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/cinema_pics/c5.jpg' | relative_url }}" alt="" title="buy tickets"/>
    </div>
</div>
<div class="caption">
    Above is an example of purchasing two tickets. The user is then prompted to save the tickets under a name. 
</div>

<div class="row justify-content-sm-center">
    <div class="col-sm mt-3 mt-md-0">
        <img class="img-fluid rounded z-depth-1" src="{{ '/assets/img/cinema_pics/c6.jpg' | relative_url }}" alt="" title="buy tickets"/>
    </div>
</div>
<div class="caption">
    After purchasing tickets, seats start becoming grayed out to indicate unavailability. 
</div>

## How it was built

This was made using the defunct `hsa.Console` library. 

There are a total of two classes at work, `Drawing.java` and `Theatre.java`. `Drawing.java` is called inside `Theatre` to draw the splashscreen animation for the program.
All other code, including file I/O, keyboard listeners, and menu navigation is within `Theatre`.

Check out the full project code [here](https://github.com/thejammerr/Theatre-Widget){:target="_blank"} on my Github.

## Challenges

Since this was my first time animating things on screen, it was difficult for me to plan out the animations and its coordinates. 
I had to resort to *painfully* hand draw a plan with all the coordinates marked, so that I wouldn't get lost when coding it.
