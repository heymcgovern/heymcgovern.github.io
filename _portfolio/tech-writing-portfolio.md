---
title: My portfolio (you're here)
date: 2022-05-01
order: 100
featured: false
internal_only: false
category: General
customer: Me!
description: >
  A home to call my own on the internet! I built this site so I can let folks know about the projects I'm working on.
image:
  alt: A screenshot of my portfolio homepage.
  thumb: assets/img/my-portfolio.png
  full: assets/img/my-portfolio.png
stakeholders:
  - Me!
tools:
  - Git
  - Jekyll
  - HTML & CSS
  - Markdown
  - Liquid syntax
layout: portfolio-item
---
Lots of folks in tech know they should have a portfolio, but it's often time consuming or expensive to set one up.

I built this site using Jekyll and GitHub Pages. I created templates myself, using [my knowledge of Liquid syntax]({{ "portfolio/liquid-syntax-reference" | relative_url }}) and HTML & CSS.

To make it quick to add new projects, I created a collection called `portfolio`. Each portfolio item has key info in front matter, and I set the template up so it lays out that information for me. For example, tools and stakeholders are a simple list in the front matter for each project.

The workflow leans on my experience of docs-as-code. I clone a copy of the Git repo, create new Markdown files, then commit and push. Jekyll builds those Markdown files into a lovely static site using the templates that I created.

I added Vale for prose linting, helping me make sure that the language I use is consistent.

My previous portfolio was a simple HTML page that I built myself. This iteration should be easier to keep up-to-date! 🤞
