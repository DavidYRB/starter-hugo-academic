---
title: Warehouse Prototype Develpment
summary: A project to build a warehouse mobile robot for Staple's fullfilment centers
tags:
- mobile
date: "2017-04-27T00:00:00Z"

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
# slides: example
---

The project was aiming to build a warehouse robotics stack for Staples' fulfillment center. As a main participant, I built a 10m * 5m test environment with precisely allocated QR codes. By consuming the image, IR, encoder data from the prototype robot, I created a path planning algorithm and a controller that enables the warehouse robot to move from any start point to end point stably while carring a 500lb pod. 