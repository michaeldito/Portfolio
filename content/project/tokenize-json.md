+++
# Date this page was created.
date = "2017-10-17"

# Project title.
title = "Tokenizing a JSON String"

# Project summary to display on homepage.
summary = "Tokenizing a JSON string with a lexical analyzer."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/tokenize-json.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Cplusplus", "Data Structures"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "project-imgs/tokenize-json-wide.png"

+++

After building our skills parsing linearly/recursively nested lists, it was time to parse a JSON string. The goal of the project was as follows: When given a JSON string, our lexical analyzer will parse the string and create a Token whenever it runs into one - allowing the user of 'Lex' to get tokens for each part of the JSON string. The solution required an understanding of how Lex was doing it's job (parsing the string). All Lex does is parse the string, and create tokens, so it needs to be told where to start and when to stop when creating these tokens. Each time it stops, it will have a token ready for the user. After completing this assignment recursion began to come naturally, and we were ready to put the tokens we generated to good use.

Check it out [here](https://github.com/michaeldito/SSU-CS-315-Data-Structures).

Next up: [Recursive List Nodes]({{< relref "recursive-list-nodes.md" >}})
