---
author: "Geoffrey Liu"
title: "Week 2: 2D Design & Cutting"
date: 2023-02-06
description: "Using a laser cutter and vinyl printer"
thumbnail: pictures/sew.png
---

I was on the waitlist for the class and joined 1.5 weeks late so my documentation starts on Week 2 :). This week, I worked on:

1. developing the website to document my progress throughout the course
2. Working on 2D design and laser printing using Fusion360
3. Thinking about final project ideas

# Website creation

I have pretty much no experience in front-end web development, most of my skills are in backend development and database stuff. I chose to develop this website using Hugo. [Hugo](https://gohugo.io) is an open source static site generator written in [Go](https://go.dev) and supports TOML, YAML and JSON data file types and Markdown/HTML content files. Apparently it is also the fastest static site generator out there.

I chose this method because using a static website generator seemed like a middle ground between from-scratch web development and using the template provided by the course instructor.

To get started, I followed the [Hugo getting started guide](https://gohugo.io/getting-started/quick-start/) to add some content. Hugo builds pages off markdown files which are relatively simple to understand. There are a few components that I had to read into, mostly:

1. Hugo's config file `config.toml`
2. Folder structure
3. Themes
4. Pushing it onto Github Pages

Hugo's config file is quite readable, think of this as an options page. Hugo's folder structure is also quite intuitive, the `content` folder contains all the markdown files and the `static` folder contains all the static files (images, css, js, etc). The `themes` folder contains the theme that the website is using. For themes, I started of with the [Blist theme](https://github.com/apvarun/blist-hugo-theme), but I found it to be a bit too complex for my liking so I went down a rabbit hole of trying to figure out how to turn off some of the elements. It turns out I just had to edit 5-6 html files to get to the current layout. Adding pictures onto the website was quite challenging since I was basically guessing the path to the image, it turns out the homepage starts off the root directory and the content page starts off in the content directory. I also had to figure out how to push the website onto Github Pages, which was a bit of a pain since I the default GitHub Actions workflow script provided by Hugo didn't work straight away and I had to add a couple of dependency install steps. I also had to change the `baseURL` in the config file to the Github Pages URL.

## Final project ideas


## 2D Design: my first laser print



<!-- 
![Sewing Machine](../images/sew.png) -->
