# Introduction
You're probably looking for samples of my work. Since some of it would be better suited with an explanation and some of it isn't even on Github, I've tried to compile a summary here of projects I've worked on. This will serve as a spring board for your journey into the vast wilderness of my code and just what my purpose was for building it.

## Rails Todo List Code Sample - 2013
During a technical interview, I was asked to build a todo list web app. The requirements were that it needed to be user-driven (each user has their own todo list), it needed to be a single-page app, and it needed to communicate to the server via a RESTful API. I decided using Rails on the backend and AngularJS/Bootstrap on the frontend would be best suited for these requirements. The client-side application is compiled with Grunt and Browserify and delivered statically for optimal performance.

* [Source Code](https://github.com/Hotcooldev/rails-todo-demo)
* Technologies: Ruby on Rails, AngularJS, Bootstrap, Grunt, Browserify, LESS, REST

## TeamGrounds - 2009
This is a project based around the idea of giving gamers a way to create profiles for their teams and connect with other players. I never completed it because another bigger opportunity presented itself, but got far enough where users could have profiles, avatars and friends. In the process I invented my own mini framework complete with its own ORM. I eventually learned that there were frameworks already out there and that writing my own wasn't really necessary. Oh well.

* [Source Code](https://github.com/Hotcooldev/portfolio/tree/master/projects_without_a_home/TeamGrounds)
* Technologies: PHP, MySQL, jQuery UI

## CSS:RPG - 2006-2007
I built a game called CSS:RPG which was a modification to another game called Counter-Strike: Source. In its heyday it had 700+ servers hosting the mod with thousands of players. It was later featured in the printed edition of PC Gamer Magazine. To this date, the game has had 200,000 downloads.

* [Source Code](https://github.com/Hotcooldev/cssrpg-archive)
* [Project Site](http://sourceforge.net/projects/cssrpg/)
* [PC Gamer Magazine, Pg. 102](http://jameskoshigoe.com/stuff/cssrpg-pcgamer.jpg)
* Technologies: C++, SQLite, Half-Life 2 SDK

## XionBot - 2004-2005
Once upon a time, someone challenged me when they said that I didn't have the skills to build my own IRC bot in a low
level language such as C. I set out to prove them wrong and that's exactly what I did. The result was a working, modular
cross-platform bot that could be scripted with the PHP language. Needless to say, I felt somewhat vindicated.

* [Source Code](https://github.com/Hotcooldev/xionbot-archive)
* Technologies: C, Sockets, PHP SAPI, IRC Protocol

## MumbleAdmin - 2010
A client wanted a way to control all of his Mumble servers (VoIP technology) via a web interface. I built this small application to his spec which worked by communicating with the Mumble daemons through [ICE RPC middleware](http://en.wikipedia.org/wiki/Internet_Communications_Engine). He never paid me so I guess it might as well be a portfolio piece right?

* [Source Code](https://github.com/Hotcooldev/portfolio/tree/master/projects_without_a_home/MumbleAdmin)
* Technologies: PHP, CodeIgniter, ICE RPC, Mumble
