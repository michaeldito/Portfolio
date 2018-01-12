+++
# Date this page was created.
date = "2017-10-17"

# Project title.
title = "The Roman Calculator"

# Project summary to display on homepage.
summary = "Executing assignment statements involving roman numeral expressions."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/roman.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Cplusplus", "Data Structures"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "project-imgs/roman-wide.png"

+++

Our first project for Data Structures, "The Roman Calculator", really set a great foundation for the rest of the course. The goal was to write a program that reads a sequence of assignment statements and executes them.

For example, the expression "a = XX + XXX * XXXV + (XXXII - XXX) + II" would assign the value of the right hand side to the variable on the left hand side.

It solidified the concept of an Abstract Data Type (ADT), and why they are extremely useful in computer science. We create ADTs so that we can view data and operations on that data without regard as to how they are implemented. It's very useful when software gets complex.

ADTs we needed to define:
- Token (to represent a roman numeral, operation symbol, etc.)
- Tokenizer (given a string, break it up into individual tokens)
- Number (given a roman numeral string or an integer, it provides methods to convert from roman to int, or int to roman)
- Symbol Table (using the map data structure it maps characters to integers, these are the results of the expression)

ADTs given to us:
- Token Iterator
- Infix To Postfix Expression Tree

We didn't need to worry about the implementation of the ADTs given to us at the time, we only needed to know what data they need, and what operations they can perform on it.

Building this project from start to finish required a lot of tests. Once each ADT was implemented, I thoroughly tested it. Once it passed all of the tests, I moved on to the next. I repeated this process until all of the ADTs were implemented. This assures that they all do their job correctly before we try to have them interact with each other.

In the end, this project helped me develop the ability to use abstraction. By doing this, I could view the requirements of the project at a very high level, and really see the big picture. All of the ADTs developed for this project were implemented in C++, using the Object Oriented paradigm.

Check it out [here](https://github.com/michaeldito/SSU-CS-315-Data-Structures).