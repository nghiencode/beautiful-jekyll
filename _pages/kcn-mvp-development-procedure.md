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
