---
title: Manipulation Hardware 
summary: A summary of major projects that related to manipulation related problems
tags:
- Manipulation
date: "2018-07-01T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: The photo is for reference only
  focal_point: Smart

links:
# - icon: twitter
#   icon_pack: fab
#   name: Follow
#   url: https://twitter.com/georgecushen
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""

# Slides (optional).
#   Associate this project with Markdown slides.
#   Simply enter your slide deck's filename without extension.
#   E.g. `slides = "example-slides"` references `content/slides/example-slides.md`.
#   Otherwise, set `slides = ""`.
---

As a co-op, I worked on projects related to end-effectors which will be used to solve the picking problems. I created a ROS Python package to control newly-designed end-effectors to perform picking behavior.

Afterwards, I set up a two-roboarm test station from installing station frames, configuring network hub connections, to  calibrating camera sensors. To display the station in ROS, I created an entire set of URDF files so the station can be accurately described and displayed in Rviz. 

I later expanded the ROS stack used internally to facilitate the test process of end-effectors. By creating a package that enables people to select picking points with desired angle and position in the pot through a real time 3D image on the screen, with just a click, the system will drive to the selected location and pick the object. 