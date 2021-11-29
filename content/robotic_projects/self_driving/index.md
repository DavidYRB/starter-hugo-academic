---
title: Udacity Self-driving Car Nanodegree
summary: A set of projects related to build a sefl-driving car system
tags:
- mobile
date: "2017-08-27T00:00:00Z"

# Optional external URL for project (replaces project detail page).
external_link: ""

image:
  caption: Photo by rawpixel on Unsplash
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
# slides: example
---
- Developed a PID controller and a MPC controller  to drive a vehicle in a simulator track (Control) 
- Programmed a particle filter to localize a vehicle with sensor information with RSME less than 0.4 (Localization) 
- Created an Extended Kalman Filter fusing Radar and Lidar data to estimate pedestrian’s position with RSME less than 0.1 (Sensor Fusion) 
- Generated a dataset of vehicles (featuring by spatial binning color, color histogram, and histogram of gradient (HOG)) and used LinearSVC to train a car classifier acquired 98.3% accuracy (Machine Learning) 
- Detected lane lines and marked driving area with polynomial-fit boundary in video with sobel threshold and color threshold binary images from each frame (Computer Vision) 
- Trained a traffic sign classifier (LeNet) with preprocessed 43-class (50,000+ images) on AWS with validation accuracy with 94.3% and test accuracy 94% (Deep Learning) 
- Controlled a vehicle to drive within a track by a model (LeNet) which is trained with collected dataset of human drive (Deep Learning)
