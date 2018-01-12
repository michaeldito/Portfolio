+++
# Date this page was created.
date = "2017-10-28"

# Project title.
title = "Worm"

# Project summary to display on homepage.
summary = "The classic video game written in C++, and using the linux screen manipulation library, Curses."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/worm.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Cplusplus", "Data Structures"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "project-imgs/worm-wide.png"

+++

Our final project in Data Structures was Worm, the classic video game. The specifications for this project were to implement the game in the following manner. The worm will move on the screen in the direction specified by the user, and if the worm eats a munchie of value N, for the next N turns it should grow. If the worm hits a wall, or itself, it dies, and the game is over.

One goal of the project was to learn how to use the linux screen manipulation library _curses_. The game is to be displayed using curses, so that the worm looks like it's fluidly moving around the screen at the top left corner of the terminal. This is where the project gets interesting. Curses functions run in constant time O(1), so if the game logic takes any longer than that, the game will begin to appear out of sync.

The trick was to use a few data structures so that the entire game is executed in constant time! First, we need to represent the grid that the worm is moving around on. This can be done using a 2D array. Next, we need to have direct access to each location on the screen that is available for a munchie (ie. locations that are not occupied by the worm). For this, we can use an Inverted List that contains screen coordinates. Finally, we need to represent the worm. In order to avoid updating each screen location that a segment of the worm occupies, we really only need to update the screen where it's tail and head are. To do this, we can use a Circular Queue of coordinates!

Once the three main data structures were defined, the biggest obstacle became figuring out the algorithm to move the worm around. It was challenging because each time one data structure was modified, you had to make sure you modified the other data structures accordingly.

In the end, this project turned out to be one of my favorites. The idea behind the game is so simple, but to implement it extremely efficiently it required careful use of a few data structures.

Check it out [here](https://github.com/michaeldito/SSU-CS-315-Data-Structures).