---
title: Paddle Invoice API microsite
date: 2022-12-01 
order: 5
featured: false
internal_only: false
category: API
customer: Paddle
description: >
  Comprehensive API and webhooks reference to support the release of a new invoicing platform.
image:
  alt: Screenshot of the in-game Shop docs homepage
  full: assets/img/paddle-invoice-api.png
  thumb: assets/img/paddle-invoice-api.png
samples:
  - title: Go to Paddle Invoice API microsite
    type: link
    link: https://paddle.stoplight.io/docs/invoice-api-reference
stakeholders:
  - Developers
  - Product
  - Developer Experience (DX)
  - Solution architects
tools:
  - Open API spec
  - REST APIs
  - JSON
  - Postman
  - Stoplight
impact:
  - 🚀 Key part of our successful public test and wider release.
  - 🤗 Helped teams at Paddle get an understanding our new Invoice platform.
  - 🤑 Key sales tool for solutions architects selling Paddle to customers.
  - 🪝 Let us test a way of handling webhook signature verification.
layout: portfolio-item
---
Paddle has an invoicing solution, letting enterprise SaaS companies create and issue invoices for subscriptions. As a relatively recent addition to the platform, it didn't launch with an API. It's a key requirement for enterprise customers who typically hook their invoicing platform up to a CRM or ERP solution.

I worked with the engineering team who developed our Invoicing tool to create comprehensive documentation for a new set of APIs. I bedded into the team, joining stand-ups, backlog refinement meetings, and other scrum ceremonies to get a good idea of the context. I created a content plan for supporting resources, such as guides on authentication and versioning, and reviewed the draft API specs the team were using.

To write content, I created a Stoplight project and backed it to GitHub. I used Stoplight to create the OpenAPI specs initially, using an IDE to refine the raw OAS and abstract parameters and properties in a way that made sense for us. For written content, I used an IDE and linted prose using Vale.

I met with the product manager and engineering manager to review content regularly. I shared my progress using pull requests in GitHub and used Stoplight's versioning feature to let non-technical folks preview content.