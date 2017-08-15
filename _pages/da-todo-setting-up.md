---
permalink: "/da-todo-setting-up/"
layout: page
title: "TodoApp with PouchDB/CouchDB"
subtitle: "Step 1: Setting up project using start-react-native and some dependencies"
---

## Step 1: Install NodeJS

Following instruction at [NodeJS](https://nodejs.org/en/) home page.

## Step 2: Install `nvm`

```bash
nvm install node
```

## Step 3: Using latest NodeJS version to install `create-react-native-app` and creating new project

```bash
nvm use node
npm install -g create-react-native-app
create-react-native-app TodoApp
cd TodoApp
yarn add pouchdb-react-native native-base
```

## Step 4: Ready to start

Visit [https://expo.io](https://expo.io) for installing Expo to your device (iOS or Android)

```bash
yarn start
```

Capture QR code and happy coding!

Next step: [Setting up CouchDB server.](/da-todo-setting-up-couchdb)