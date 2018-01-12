+++
# Date this page was created.
date = "2017-10-26"

# Project title.
title = "Measuring Application Performance"

# Project summary to display on homepage.
summary = "Scripts for measuring application performance with ApacheBench."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/apache.jpg"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Bash", "Python", "Plotly", "Google Cloud Platform", "ApacheBench"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = ""

+++

In our Cloud Systems Architecture course we were introduced to ApacheBench, a popular
benchmarking tool. We created a number of REST servers and a load balancer, and tested
the performance of our application with varying numbers of REST servers running, and
at different concurrency levels. Instead of manually running each test and copying the
results into a spreadsheet, I decided to write a Bash script to do all of that for me.
The script writes data to files, and when it's finished I ran a python Plotly script to
generate a performance graph.
