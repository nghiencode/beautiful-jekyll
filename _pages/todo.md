---
permalink: "/todo/"
layout: page
title: TodoApp with PouchDB/CouchDB
subtitle: TodoApp with React Native, PouchDB, CouchDB and zero backend
---

# Requirements

The TodoApp will help us memorize somethings we need with priorities.

We can create/edit/remove/rearange/mark done todos.

Our requirements are TodoApp can work on both online and offline.

User can have one or many devices such as an iPhone and an iPad and and Android device.

When user update todo by one device, the other device(s) will change correspondingly.

Then we get some conclusions:

1. App can run on most mobile devices (iOS and Android are majority)
2. App can work on both online and offline
3. App can sync data from offline to online and vice versa

# Choosing technologies

Based on requirements, we get some decisition:

1. Using `React Native` with `start-react-native` (Expo) because we don't need any function need `link` to platform.
2. Using using `PouchDB` for client and `CouchDB` for server because we need sync data.
3. Using `Nativebase`, this is a trivial choice because it help we so much in laying out.

# Implementation steps

1. Setting up project using `start-react-native` and some dependencies.
2. Setting up CouchDB server, PouchDB client.
3. Laying out.
4. Using PouchDB to store data.
5. Syncing data.
6. Ready for production.
