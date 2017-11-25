+++
# Date this page was created.
date = "2017-10-17"

# Project title.
title = "Maze GUI"

# Project summary to display on homepage.
summary = "Expanding the maze game into a GUI with Microsoft Foundation Classes (MFC)."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/ditoP3.bmp"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Cplusplus", "MFC"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "project-imgs/ditoP3.bmp"

+++

This project expanded upon the console version of the maze game by adding a Graphical User Interface. Since the game logic was already complete, the main challenge posed by this project was learning how to use the Microsoft Foundation Classes (MFC) library code provided to us, and understand event driven programming. We derived our application and window from MFC classes, and used inherited functions from these classes to update the window the game is played on. In order for the game to respond to clicks and button presses, we had to use message handlers for the first time. This was quite a challenging project, and it really provided insight as to how much is going on under the hood for GUI applications. It also made me appreciate the simplicity of event driven programming in javascript.
