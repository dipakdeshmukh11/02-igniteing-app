## npm init

package name: (day-02)
version: (1.0.0)
description: react app by dipak
entry point: (App.js)
test command: jest
git repository: git repo link
keywords: react
author: Dipak Deshmukh
license: (ISC)

## npm i -D parcel

## npm i react

## npm i react-dom

in index.html file

  <script type="module" src="App.js"></script>

in App.js file first two line
import React from "react";
import ReactDOM from "react-dom/client";

in package.json file

1. remove : "main": "App.js",
2. configure in script:
   "scripts": {
   "start": "parcel index.html",
   "build": "parcel build index.html",
   "test": "jest"
   }

## npm start
