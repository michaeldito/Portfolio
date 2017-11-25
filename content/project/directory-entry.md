+++
# Date this page was created.
date = "2017-10-27"

# Project title.
title = "Directory Entry"

# Project summary to display on homepage.
summary = "Building the internal representation of a directory hierarchy, a rooted tree data structure."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/directory.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Cplusplus", "Data Structures"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "project-imgs/directory-ex.png"

+++

This project was the culmination of quite a few labs and projects. After expanding our recursive list parser, the task was to parse a JSON string and populate a Directory Entry with it's contents. This ADT is a rooted tree data structure composed of Directory Nodes. The nodes are either files or directories. Files are the leaves, and directories are recursive nodes that may contain files and/or more directories. Attributes of a Directory Entry were two Directory Nodes: rootDir and cwd. Operations of this ADT include some of the most commonly used Unix commands (ls, pwd, cd, find), their variations, and other operations commonly used in tree structures (depth, duplicate, hasSubstructure, areTheSame, move).

Depth-First-Search was used quite often in implementing the operations Directory Entry required. It was used in: cd, ls, duplicate, find, and move. Once the data structure was complete, I built a function that simulates a terminal environment. It builds a directory from a JSON file, and then allows the user to perform any of the operations previously mentioned.

Their was a lot to take away from this project. We built up our skills for weeks to be able to tackle this project. Mapping out the steps needed on paper helped as always. Taking the time to write some pseudo code and explore the project before diving into the terminal saved me a lot of debugging - and having to redesign the structure of my solution. The next time I undertake a big project, I'll know that I need to take small steps, plan things out, test each module, and then move on to the next task.
