---
permalink: "/kcn-mvp-development-procedure/"
layout: page
title: MVP development procedure
---

A MVP typical included Backend + Web client + Mobile client

Web client (SPA) and mobile client interact with Backend by RESTFul API. They can use an offline database or not.

Web client and Mobile client mainly based on JS, all it's dependencies can deal with NVM/NPM realy easy to setup and init data.

Backend is a nother case, it depend on many thing from database, programming language, broker...

We can list some of it:

* Database: Postgres / MariaDB / CouchDB / MongoDB
* Web server: Nginx
* Programming language: PHP 7.x and it's dependencies / extensions
* Broker: RabbitMQ / Redis
* NodeJS

All source code we can use Github

The procedure below assume that we already have an idea about product and all developers are belonged to repo's collaborators.

After that, we have some steps:

**Step 1:** Setup development environment -> Using Docker + NPM/NVM
**Step 2:** Clone source code from Github
**Step 3:** Follow Github repo's instruction, seeding data if needed.
**Step 4:** Run test -> if fail: back to step 3
**Step 5:** Make conversation with PM or team leader about which issue you can implement then pick one.
**Step 6:** Estimate necessary time for implementing, PM will assign that developer to Github issue and create cart(s) on Trello for time tracking.
**Step 7:** Developing, writing test cases.
**Step 8:** Push code and create new pull request.
**Step 9:** Code reviewing + editing n times till good.
**Step 10:** Merge code + run test on production environment (CI), if fail -> back to step 9.
**Step 11:** Mark Github issue resolved, move Trello card(s).
**Step 11:** Back to step 5.
