# RPI Desktop Application

## Introduction

* Date: Feb. 2016 - Apr. 2016 
* Project Manager : Seyha HENG (PPS) 
* Developers : Ly TANG (ALLWEB intern), Lyta LY (ALLWEB intern) 
* Technologies : Electron.io, NodeJS, AngularJS

## Roadmap

* Replace grunt by gulp (including karma test cases)
* Update bower dependencies
* Update npm dependencies
* Write proper documentation


# Original Template

## SB Admin v2.0 rewritten in AngularJS

This project is a port of the famous Free Admin Bootstrap Theme [SB Admin v2.0](http://startbootstrap.com/template-overviews/sb-admin-2/) to Angular Theme.

Find out more [Free Angular Themes at StartAngular.com](http://www.startangular.com/).

## Installation
####1. Clone this project or Download that ZIP file

```sh
$ git clone https://github.com/start-angular/sb-admin-angular.git
```

####2.  Make sure you have [bower](http://bower.io/), [grunt-cli](https://www.npmjs.com/package/grunt-cli) and  [npm](https://www.npmjs.org/) installed globally
 
 
```sh
$ sudo apt-get install npm
$ sudo npm install -g grunt-cli
$ sudo npm install -g bower
```
####3. On the command prompt run the following commands

```sh
$ cd `project-directory`
```
- bower install is ran from the postinstall
```sh
$ npm install 
```
- a shortcut for `grunt serve`
```sh
$ npm start
```
- a shortcut for `grunt serve:dist` to minify the files for deployment
```sh
$ npm run dist 
```