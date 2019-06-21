<h1 align="center"> SLACK-LACKEY </h1> <br>
<p align="center">
  <a href="">
    <img alt="slack-lackey" title="slack-lackey" src="./assets/whiteboards/slack-lackey.png" width="150">
  </a>
</p>

<p align="center">
  Code saving and sharing. Built with Nodejs.
</p>

<p align="center">
  <a href="https://slack.com/">
    <img alt="Slack" title="slack" src="https://marker.io/vendor/img/logo/slack-logo.svg" width="140">
  </a>
</p>

## Table of Contents


- [Links and resources](#links-and-resources)
- [Introduction](#introduction)
- [Tools](#tools)
- [Features](#features)
- [Set up](#Set-up)
- [How to use](#How-tou-se)
- [UML](#uml)
- [Documentations](#Documentations)
- [Contributors](#contributors)
- [Feedback](#feedback)


## Links and resources

* [Aws](https://github.com/slack-lackey/docs/wiki)
* [Heroku](https://slack-bot-api-server.herokuapp.com)


## Introduction

[![Build Status](https://travis-ci.com/slack-lackey/api-server.svg?branch=development)](https://travis-ci.com/slack-lackey/api-server)
[![Coveralls](https://img.shields.io/coveralls/github/gitpoint/git-point.svg?style=flat-square)](https://coveralls.io/github/gitpoint/git-point)


A tool for saving and sharing code to gist inside of slack channel. If you're looking for a way to save a code snippet in Slack, Slack-lackey is the best app for it.

## Tools

<a href="https://opencollective.com/git-point/sponsor/9/website" target="_blank"><img src="https://a.slack-edge.com/4f28/img/slack_api_logo.png" height="40"></a>
<a href="https://opencollective.com/git-point/sponsor/9/website" target="_blank"><img src="https://cdn-images-1.medium.com/max/1600/1*J8O2xd9ZqxWr2x6EP4MHmg.png" height="40"></a>
<a href="https://opencollective.com/git-point/sponsor/9/website" target="_blank"><img src="https://mlab.com/base/img/cobranded-logo-onlight.svg" height="40"></a>
<a href="https://opencollective.com/git-point/sponsor/9/website" target="_blank"><img src="https://www.pentoz.com/wp-content/uploads/2018/12/Amazon-Web-Services.png" height="40"></a>
<a href="https://opencollective.com/git-point/sponsor/9/website" target="_blank"><img src="https://crazydost.com/wp-content/uploads/2018/02/AAEAAQAAAAAAAAqwAAAAJDVlOTM1OTk3LTM2MzgtNDMwYi1hNWMxLTY2NzBiOTk4MmNmOQ.jpg" height="40"></a>


## Features

A few of the things you can do with Slack-lackey:

* Save code snippet to your gist
* Save code block to yous gist
* Save edited code to your gist
* Share your gist link into the channel
* Get all the gists you save


<p align="center">
  <img src = "./assets/whiteboards/save.png" width=700>
</p>
<p align="center">
  <img src = "./assets/whiteboards/share2.png" width=700>
</p>
<p align="center">
  <img src = "./assets/whiteboards/get.png" width=700>
</p>

## Set up

#### Environment requirements

- Clone or download the [Bot-server repo](https://github.com/slack-lackey/bot-server)
- `npm install` to install dependencies
- Create a new app to your workspace follow the instruction of [Creating slack app](https://github.com/slack-lackey/bot-server/blob/development/README.md)
- new a .env file, set all the keys needed for the app

**Keys are required for building your own bot. **

#### Running the App
- `nodemon` or `npm start` to start the app


## How to use

In your workspace:
- When receive or send a code block or snippet, click yes if you want to save it; click no if you don't.
- When successfully saved to gist, click yes if you want to share to the channel; click no if you don't.
- If you want to get all the gists that previously saved, input `get my gists`.

## UML
* ![UML](https://i.imgur.com/a93LCC1.jpg)

## Documentations

* [Project wiki](https://github.com/slack-lackey/docs/wiki)
* [Group agreement]()
* [User stories]()

## Contributors

This project is brought to you by these awesome contributors.

<a href="https://github.com/billybunn" target="_blank"><img src="./assets/whiteboards/billy-bot.png" height="40"></a>
<a href="https://github.com/ChristopherKnightMerritt" target="_blank"><img src="./assets/whiteboards/chris-bot.png" height="40"></a>
<a href="https://github.com/etrainor" target="_blank"><img src="./assets/whiteboards/erin-bot.png" height="40"></a>
<a href="https://github.com/Wei9023" target="_blank"><img src="./assets/whiteboards/vanessa-bot.png" height="40"></a>

## Feedback

Feel free to send us feedback on [file an issue](https://github.com/slack-lackey/docs/issues/new). Feature requests are always welcome. 

