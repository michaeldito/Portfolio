+++
# Date this page was created.
date = "2017-10-17"

# Project title.
title = "Maze"

# Project summary to display on homepage.
summary = "A Maze game, written in C++."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/maze.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Cplusplus"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "project-imgs/maze-wide.png"
caption = "My caption :smile:"

+++

A project from our Programming II course at Sonoma State, the maze game. The goal of the game is quite simple, move the player through the maze to reach the goal! Their were quite a few challenges in implementing this project. How should the maze be generated? The solution was a recursive division algorithm, the first difficult one I encountered in my programming career. Looking back, it is quite simple! First we divide the maze into four squares, then we pop open a door on three of the inner walls. Then we repeat this process, recursively, for each of the four squares. Once the squares reduce to a small enough size, we have reached our base case.

A few lessons learned from this project:
- How to create a dynamic 2D array
- Stay within your array bounds (or risk the dreaded SEGFAULT)
- How to design a game loop
- Designing algorithms with pseudocode
