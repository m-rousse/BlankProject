# A Blank Project

The goal of this project if to provide a sane start for each project I do.
It provides default configurations files like `package.json` for npm, `GruntFile.js` for grunt.

I will add the commands for each particular framework as I use them or when I remember this project.

## NPM

The node package manager. The `package.json` has been generated using `npm init` and filled with default values.
The licence choice is good to keep for an open-source web-application.

## Grunt

It is an automation tool to help you develop, build and deploy your project. (Like an improved Makefile).
The `GruntFile.js` is a generic one.
To use it you must install grunt with npm :
```bash
npm install grunt --save-dev
```
Then configure the assets in the GruntFile.
Interesting assets :
- grunt-contrib-watch
- grunt-contrib-less
- grunt-contrib-clean
- grunt-contrib-uglify
- grunt-contrib-copy
- grunt-line-remover
- grunt-php
- grunt-nodemon

A list of assets is available at : http://gruntjs.com/plugins

## Bootstrap

A css framework to design quickly web applications. The page load bootstrap and JQuery.
The css, js and fonts files/folders a required to use this template.

## Clone this repo

To clone this repo without having the whole git repo and folder arch, you can use :
```bash
git clone --depth=1 https://github.com/m-rousse/BlankProject.git NewProject
rm -rf !$/.git
```
