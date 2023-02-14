---
author: "Geoffrey Liu"
title: "Week 2: 2D Design & Cutting"
date: 2023-01-30
description: "Making a website, learning CAD, using a laser cutter and vinyl printer"
thumbnail: /images/week1_thumbnail.jpg
---

I was on the waitlist for the class and joined 1.5 weeks late so my documentation starts on Week 2 :). This week, I worked on:

1. developing the website to document my progress throughout the course
2. Working on 2D design and laser printing using Fusion360

# Website creation

I have pretty much no experience in front-end web development, most of my skills are in backend development and database stuff. I chose to develop this website using Hugo. [Hugo](https://gohugo.io) is an open source static site generator written in [Go](https://go.dev) and supports TOML, YAML and JSON data file types and Markdown/HTML content files. Apparently it is also the fastest static site generator out there.

I chose this method because using a static website generator seemed like a middle ground between from-scratch web development and using the template provided by the course instructor.

To get started, I followed the [Hugo getting started guide](https://gohugo.io/getting-started/quick-start/) to add some content. Hugo builds pages off markdown files which are relatively simple to understand. There are a few components that I had to read into, mostly:

1. Hugo's config file `config.toml`
2. Folder structure
3. Themes
4. Pushing it onto Github Pages

Hugo's config file is quite readable, think of this as an options page. Hugo's folder structure is also quite intuitive, the `content` folder contains all the markdown files and the `static` folder contains all the static files (images, css, js, etc). The `themes` folder contains the theme that the website is using. For themes, I started of with the [Blist theme](https://github.com/apvarun/blist-hugo-theme), but I found it to be a bit too complex for my liking so I went down a rabbit hole of trying to figure out how to turn off some of the elements. It turns out I just had to edit 5-6 html files to get to the current layout. Figuring out how to get GitHub Actions to build my site was a pain since the default script provided by Hugo didn't work.
## 2D Design: my first laser print

<!-- 
![Sewing Machine](../images/sew.png) -->
## Fusion360

To learn Fusion360, I followed a few different Youtube tutorials. I decided to choose a 12oz aluminium can and my iPhone as objects to model in Fusion360, my thought to learn how to model a round object and a flat object with small details. 

For the can, I thought it would be easiest to model the cross-section and then use the rotate tool to get a 3d model. To model the cross section, I just measured the height and diameter of the can. I then found a front-on stock image of a standard coca-cola can and placed that image as a canvas onto Fusion360. Canvases can be calibrated by selecting points on the canvas and specifying a dimension, this allowed me to scale the image to the exact dimensions of the can. I then used the spline tool to trace around the irregular edges of the can to complete the cross-section. Then using the rotate tool, I created the 3D can body.

![Can cross-section](/content/blog/images/w2_1.png)
