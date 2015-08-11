[![Code Climate](https://codeclimate.com/github/kevinlanzon/lizard-king/badges/gpa.svg)](https://codeclimate.com/github/kevinlanzon/lizard-king)
Lizard King
==========

A project to find the funniest image or gif online. Built with [Meads](https://github.com/meads58), [Diego](https://github.com/jdiegoromero) and [Ed](https://github.com/eddbrown) for the three day Makerthon at Makers Academy.

Requirements
----
-  choose the funniest picture/gif between two pictures
-  there is a funniest picture/gif leader board based on votes

Technologies used
----
- JavaScript
- AngularJS
- NodeJS
- Express with EJS templates
- Karma for unit testing
- Protractor for integration testing
- HTML5
- CSS3
- Bootstrap
- Git
- Sublime Text


Setup
-----
```sh
$ npm install
$ bower install
$ node app.js
```

Screenshot
---
<div align="center">
        <img width="105%" src="/public/images/homepage.png">
</div>

Heroku (live)
-----

[LizardKing](https://lizardking.herokuapp.com/)


How to clone this repo
----
```sh
$ git clone git@github.com:kevinlanzon/lizard-king.git
```

How to run tests
----
```sh
$ cd lizard-king
$ karma start
```

Future Features
-----
- Add a persistence layer for the results with a database
- Google scraper extension to build the gif list
- Implement the Elo algorithm for scoring wins and losses
