+++
# Date this page was created.
date = "2017-10-17"

# Project title.
title = "Recursive List Nodes"

# Project summary to display on homepage.
summary = "Building recursive list nodes with a lexical analyzer."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/rec-list-nodes-tall.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Cplusplus", "Data Structures", "Recursive Lists"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "project-imgs/rec-list-nodes-wide.png"

+++
Before beginning this project, it was clear that in order to build complex software projects you must take small incremental steps. At each step, you need to thoroughly test your program. Once it's working properly, you can continue on to the next hurdle. Then, repeat this process until the project is complete.

Once we were able to tokenize a JSON string with a lexical analyzer, we could begin doing much more exciting work. All along, we were building the skills necessary to build the internal representation of a directory hierarchy, which we later represent as a rooted tree data structure. In this phase of the project, the goal was to use the tokens our lexical analyzer would give us to build List Nodes - which will later hold information about files or directories.

Check it out [here](https://github.com/michaeldito/SSU-CS-315-Data-Structures).

Next Up: [Directory Entry]({{< relref "directory-entry.md" >}})
