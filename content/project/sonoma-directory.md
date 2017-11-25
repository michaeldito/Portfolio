+++
# Date this page was created.
date = "2017-10-17"

# Project title.
title = "Sonoma Directory"

# Project summary to display on homepage.
summary = "A custom Alexa skill that retrieves Sonoma State faculty information."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/ssu-directory.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["AWS", "DynamoDB", "Node.js", "Alexa"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "project-imgs/ssu-directory.png"

+++

This was a group project I was a part of for our Software Design and Development course at Sonoma. It served as an introduction to understanding the Alexa Platform, Amazon's Lambda, and how to create a Voice User Interface (VUI). Our idea was a simple, manageable product that we could complete in a few months. Sonoma Directory allows a user to retrieve information for faculty members at Sonoma State. The information can be any combination of: email, office location, and phone number. It was developed using Node.js and the alexa-sdk, we used a python selenium script to localize our data, and we stored it in DynamoDB.

A brief example:  
A user of the program might say, "Alexa, ask Sonoma Directory what the email is for Professor Smith". To which Alexa would respond, "I found an email for Professor Smith. It is smith@sonoma.edu".
