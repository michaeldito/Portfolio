+++
# Date this page was created.
date = "2017-10-29"

# Project title.
title = "Active v2"

# Project summary to display on homepage.
summary = "Active, an activity logging program, implemented as a Node.js web application."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/active-tall.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Node-js", "Javascript", "PostgreSQL", "Pug", "Heroku", "CSS"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "project-imgs/active-wide.png"

+++

This is my second implementation of Active, an activity logging application. After completing our Database Management Systems Design course at Sonoma State, I decided Active would be a great project to further practice the MVC paradigm in web application development. In our database course, we used MySQL, and had multiple labs that introduced us the MVC paradigm by building web applications with Node.js. For my second go at Active, I decided to continue practicing Node.js, and to learn a new sql database, PostgreSQL. A friend of mine had also recommended an HTML templating language called Pug, so I chose that in favor of what I had previously used, EJS.

Once the backend had been set up. I chose a very minimal bootstrap theme to style the application. During the styling, I ran into issues with things not looking how they should. So I took this opportunity to learn more CSS. Once the application was ready for deployment, the last challenge remained. Choosing a cloud service provider, and hosting the application through their services.

Since two of my upcoming courses at Sonoma were going to be using the Google Cloud Platform, and Amazon Web Services, I opted for Heroku. With the help of their very clear online documentation, Active is now live on Heroku!

[Active](https://active-app.herokuapp.com)
