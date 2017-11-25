+++
# Date this page was created.
date = "2017-10-28"

# Project title.
title = "Algorithms with Numbers"

# Project summary to display on homepage.
summary = "Arithmetic operations using binary arrays to represent bit level operations."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/algs-with-nums-tall.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Python"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "project-imgs/algs-with-nums-wide.png"

+++

This project was split into two parts for our Analysis of Algorithms course at Sonoma. The goal of the project was to gain an understanding of bit-level operation run times for various arithmetic algorithms. To do this, we used binary arrays in Python. These binary arrays were just lists with elements being either 0 or 1. During implementation, it was import to remember which ends of the list were the most significant and least significant bits (big endian vs little endian). I learned that passing variables as parameters in Python is a bit different than in C++ (by reference/by value). After part 1, we expanded this project so that we could perform RSA Encryption/Decryption.
