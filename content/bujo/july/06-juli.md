---
title: Webpack Build tool
date: "2019-07-06T19:18:00.000+00:00"
revision: 1
series:
- DailyLogs
categories:
- frontend
- design
tags:
- tool
- webpack
- gridsome
---

SitCom
: Situation Comedy

tl;dr
<!-- more -->

## Web Design vocabulary

* Typography
  * bold text mixed with a nice script font
* Primary colour
  * from logo
* Design Tools
  * Wireframes drawing
    * [sketch](https://www.sketch.com/)
    * How to design a website wireframe on ubuntu linux?
      * webflow - cloud based solution
      * **draw.io** linux desktop app
  * Fonts
    * google chrome plugin
* Links
  * external/outbound links
  * internal links and cross-references
  * Anchors links
* **steal** images from
  * [undraw](https://undraw.co/illustrations)
* self-closing tags `</br>`, `<style src="..." />`
* color scale in numbers
  * dark - darker - darkest
* Draw and add your own vector images and SVGs


## WEBpack

* [is like a build tool for frontend files](https://youtu.be/GU-2T7k9NfI)
* can minify asset files (html, css, js)
* starting point for webpack and then it works its way up.
  * export/import all modules and variables using `require`
* combines all files into one file
  * newly generated file needs to be `linked/imported` in html document
* Common problems it solves
  * you have multiple JS files, linked in DOM on after another, you change the order and JS link directives and you have a console error
    * Import files in correct order
* collects all js files and builds a single `dist/bundle.js` file
* Testing your app on `file` protocol has some disadvantages as it doesnt not load assets files.
  * Also in devtools, betworks tabs, all file size would be **0** as not using `http` protocol
* COnfigurations in `package.json` file

### How does webpack works

* `webpack.config.js`
* Entrypoint, multiple entrypoints
* Where to save output
* What to do during journey from, start to end - bundles, plugins
* Module Loaders - applied on each file, folder
* Plugins - applied in the end to the bundle

#### How to add fonts to website using your website generator?

##### Bullet journal website

## Gridsome

1. gridsome project to understand position css proprty
2. generate random data using faker:Plugin
