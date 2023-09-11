---
title: "Tech Stacks"
description: ""
summary: ""
date: 2023-09-07T16:04:48+02:00
lastmod: 2023-09-07T16:04:48+02:00
draft: false
images: []
menu:
  docs:
    parent: ""
    identifier: "techstacks-1"
weight: 810
toc: true
---

Welcome to the tech stacks page where we will talk about the platforms that's used to make this website possible.

## Static Site Generator / CMS

After some level of assessment on what technology makes sense and what I build, I decided on [Hugo](https://gohugo.io/) as the web platform static site generator. Main reasons are the following

- The solution should work with a static web site hosting service.
- I wanted something simple but still write some code and configurations.
- I wanted to use something that's not npm based.
- I wanted a static site generator that doesn't come bundled with a front end solution.

## Theme

We're using Doks. For the theme site please visit [https://gethyas.com/themes/doks/](https://gethyas.com/themes/doks/)

## CICD

We're using

- GitHub for code repo
- Hugo's out of the box GitHub actions for pipeline
- Azure's static web app plus hugo build preset

Currently it takes about ~1 min for code /content to be pushed and content to show up on the website.

For more information please see [https://learn.microsoft.com/en-us/azure/static-web-apps/publish-hugo](https://learn.microsoft.com/en-us/azure/static-web-apps/publish-hugo)

## Static Site Hosting and Certificates
Site hosting is being handled through Azure's free tier static web app.

Azure also offers free certificates in their free tier.

## Business Solutions and Platforms

For business related solutions and platform decisions please see [our About page](/about/).
