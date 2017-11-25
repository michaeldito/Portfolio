+++
# Date this page was created.
date = "2017-10-17"

# Project title.
title = "Recursively Nested Lists"

# Project summary to display on homepage.
summary = "Parsing recursively nested lists using a lexical analyzer."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/rec-nested-1.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Cplusplus", "Data Structures", "Recursive Lists"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "project-imgs/rec-nested-2.png"

+++

Continuing to build our parsing skills and hone our ability to think recursively, this assignment provided practice with recursively nested lists. We continued to use a lexical analyzer to parse the list into tokens. Upon inspection of these tokens, we could ask questions to determine whether or not we were in fact looking at a recursive list or not. Carefully developed conditional checks and return statements were all that was needed. In the end, we were getting even closer to be able to parse a JSON object.

Next up: [Tokenizing a JSON string]({{< relref "tokenize-json.md" >}})
