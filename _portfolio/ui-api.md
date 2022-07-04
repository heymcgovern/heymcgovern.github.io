---
title: UI API docs
date: 2022-06-01
featured: false
internal_only: true
category: API
customer: Lockwood Publishing
description: >
  Tutorials, reference guides, and code samples for an API for building UI panels.
stakeholders:
  - Developers
  - UX/UI
tools:
  - JSON
  - YAML
  - "C#"
  - Confluence
  - Jira
impact:
  - 💪 Greater awareness of what our UI tech can do.
  - 📈 More folks using our UI API to build panels.
  - 🧘 Less dev time spent digging through code or examples.
  - 🐛 Highlighted gaps and bugs in the tool, filling a backlog.
layout: portfolio-item
---
UI panels are the unsung heroes of any game. They give players information, reward them for doing things, and give them ways to spend currency.

The UI/UX team asked me to create documentation to make it easier for folks to build UIs.

I reviewed the existing docs and chatted to internal tools who build UIs to create a content plan in Jira.

* Documentation for UI elements, found by reading the C# code that handles bindings.
* First time user tutorials that walk folks through creating panels from scratch.
* Explainers that walk through what we can (and can't) do with UIs.
* Code samples and snippets, so folks can copy-paste.

I used existing panels, as well as the C# code that handles bindings, to put together samples. We use JSON and YAML in our panels, so I used those a lot in this project.

Docs live on Confluence right now, but we're exploring a docs-as-code workflow for the future 👀
