---
title: "A Short History of Testing of Software Systems"
date: 2023-08-26T12:38:17-06:00
draft: false
toc: false
images:
tags:
  - untagged
---

This post was written for my cybersecurity class assignment with [Ken Bauer](https://kenbauer.me/)

Since my first semester in school, we've been encouraged to test our projects with what may be unusual inputs and the ways our project can handle such inputs, such as a very big integer, negative integers or sometimes a zero.

It is important to notice that in the world we develop where we will face sooner or later a CI/CD working environment, where software must change constantly and teams must constantly communicate, hence there is a big priority in automating repetitive tasks such as testing with unusual inputs in order to quickly and safely integrate team contributions to the project. Thankfully, Github, the biggest collaborative software development platform has Actions which allows to test PR's and commits through a containerized cloud machine and steps to run the software in a yml file which guarantees there will be no problems in deployment in relation with OS dependencies.
{{< youtube id="yfBtjLxn_6k" >}}
However it is important to take into consideration the fact that it takes that to automate such processes and can be frustrating when starting the project or when team members device environments are too different, it's important to take that into consideration.
Also, this blog was deployed with Github Actions!