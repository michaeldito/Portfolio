+++
# Date this page was created.
date = "2017-10-30"

# Project title.
title = "Automate Application Scaling"

# Project summary to display on homepage.
summary = "Scaling virtual machines and updating a load balancer with python scripts."

# Optional image to display on homepage (relative to `static/img/` folder).
image_preview = "project-imgs/google-cloud.png"

# Tags: can be used for filtering projects.
# Example: `tags = ["machine-learning", "deep-learning"]`
tags = ["Google-Cloud-Platform", "Python"]

# Optional external URL for project (replaces project detail page).
external_link = ""

# Does the project detail page use math formatting?
math = false

# Optional featured image (relative to `static/img/` folder).
[header]
image = "project-imgs/google-cloud2.png"

+++

In our Cloud Systems Architecture class at Sonoma, we discussed topics such as virtualization and scalability.
To practice what we learned, we created a number of REST servers on the Google Cloud Platform, as well as a controller server, and a load balancing server. The goal of this assignment was to automate the load balancing process using google's APIs, and scale our application up and down using scripting. To achieve this, we were required to explore google's APIs for ourselves. This improved an important skill for developing software - being able to read through documentation to find what you are looking for.  

During the course of this assignment I discovered a very useful Python library - Paramiko. Paramiko is a Python implementation of SSHv2 protocol, and it provides both client and server functionality. From Paramiko, you can create an ssh connection to a remote server and execute commands on that server. This library allowed me to update the list of IP addresses that the load balancer was forwarding requests to.

After reviewing this project, I realized Paramiko wasn't necessary. Google provides a command line utility for you to use. After exploring 'gcloud' - the name of their CLI, I found that it supports ssh as well as scp. I could now (1) log into remote instances and execute a command using gcloud ssh, and (2) copy a file to an instance using gcloud scp.

I developed a Controller class for this project, in which I 'wrapped up' many of google's API functions so that they would be easier to call. I'm in the middle of creating a documentation website for various things I've learned from this class, and will post it here when I finish.
