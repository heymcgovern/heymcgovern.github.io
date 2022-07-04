---
title: Lua scripted API docs
date: 2022-04-01
featured: true
internal_only: true
category: API
customer: Lockwood Publishing
description: >
  Docs-as-code static site for a large Lua scripted API, used by teams to create revenue-generating content for the game.
image:
  alt: Screenshot of sample API documentation
  full: assets/img/lua-api.png
  thumb: assets/img/lua-api.png
samples:
  - title: Download sample API guide
    type: download
    link: assets/pdf/lua-api-sample.pdf
  - title: Download sample JSON screenshot
    type: download
    link: assets/img/lua-api-sample-json.png
stakeholders:
  - Developers
  - DevOps
  - Content scripters
  - Project managers
tools:
  - Mkdocs
  - Git
  - JSON
  - Markdown
  - Lua
  - Go
  - HTML & CSS
  - Jira
impact:
  - 🏁 Content teams were able to start creating content much faster.
  - 🤫 Fewer interruptions on Slack for the devs.
  - 👩‍💻 Docs live near the code, making it easy for devs to create or update docs as they work.
  - 🔀 Interoperable JSON format meant we could remix docs—even bringing code complete to Visual Studio Code!
  - 💪 Greater awareness of the power of the platform among leadership and other teams.
  - 🐛 Highlighted inconsistencies and bugs, filling a backlog of fixes.
layout: portfolio-item
---
We have an internal platform where folks can create content for the game. All the complexity of Unity is taken away and replaced by a lovely Lua API. The only problem was that there were no docs.

Folks had to either look at existing objects, dig into prototypes, wade through the Go codebase... or, worst of all, interrupt our devs on Slack 😱

I created comprehensive documentation for the Lua API. I read the Go code that handles Lua bindings, then wrote up docs explaining classes, functions, and properties. I added parameters, returns, and an example for each function.

I wrote definitions in JSON files that lived alongside the Go code. I worked with a dev to create a Python script that converted these JSON files to Markdown. After this, Mkdocs Material rendered those Markdown files and created a static website.

To make sure that our documentation is consistent and welcoming to everyone, I added Vale to our workflow. I used Google's developer style guidelines, as well as creating some in-house rules to catch common mishaps.

This was a large project, so I worked with a project manager to organize tasks. I tracked progress using Jira.

I worked with developers throughout, using pull requests in GitHub to ask questions and get feedback.
