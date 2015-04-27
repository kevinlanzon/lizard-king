[![Code Climate](https://codeclimate.com/github/kevinlanzon/lizard-king/badges/gpa.svg)](https://codeclimate.com/github/kevinlanzon/lizard-king)
Lizard King
==========

A project to find the funniest image/gif online. Built with [Meads](https://github.com/meads58), [Diego](https://github.com/jdiegoromero) and [Ed](https://github.com/eddbrown) for the three day Makerthon at Makers Academy.

Requirements
----
-  choose the funniest picture between two pictures
-  there is a funniest picture leader board based on votes

Technologies used
----
- JavaScript
- jQuery
- AngularJS
- NodeJS
- Express with EJS templates
- Karma for unit testing
- Protractor for integration testing
- HTML
- CSS
- Git
- Sublime Text


Setup
-----
- Run npm install
- Run bower install
- The server is nodeJS using ExpressJS using EJS templates. To run the webpage type 'node app.js'

Screenshot
---
<div align="center">
        <img width="70%" src="/public/images/homepage.png">
</div>

How to clone this repo
----
```sh
git clone git@github.com:kevinlanzon/lizard-king.git
```

How to run tests
----
```sh
cd lizard-king
run karma start
```
Future Features
-----
- Add a persistence layer for the results with a database
- Google scraper extension to build the gif list
- Implement the Elo algorithm for scoring wins and losses
