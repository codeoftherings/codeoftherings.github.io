---
published: true
title: My first messenger bot
layout: post
---
Hey guys,

I recently watched a bunch of developers conference hosted by major tech company and found a lot of them had common theme : bots. Facebook spoke about them in f8, Microsoft introduced a bunch of them at Build and Google showed off their messenger app 'Allo' full of intelligent bots. I got very excited about this and decided to create my own bot. I wanted to create something simple as I don’t enough experience yet to code it with machine intelligence (I’m right now starting a machine learning course).

So what I did was I created an account on a website called Heroku (heroku.com). Its an awesome website for providing a server for node is, python, ruby and lot of other backed code. They have a free developer account that gives a lot of functions and has everything you need to get started. You’re limited to only five projects for a free account but buying a subscription isn’t that expensive. So I created the bot using JavaScript and uploaded it there. I created an app in Facebook developer dashboard and linked my heroku app there. I will explain all the steps required to deploy your app in another post soon to follow. I won’t explaining the code as I’ll share the code with plenty of self explanatory comments.

My bot’s a very simple one. You give it the name of a planet in the solar system and some information you want from it – like radius, mass, density, etc. - and it will instantly provide you with it. Not very fancy, but it was quite fun to make. I’ll also explain some of the trouble I had in making the bot and tell you solutions should you face same issues. Also there will be some issues out of your control as Messenger development platform is still in beta and there are some issues. I’ll also describe them below.

Please do try this bot. A screenshot of the page:


https://www.facebook.com/AstroBot-1055047784587294/

Note:

Do not type a question mark directly after name of planet or name of the parameter desired. I haven't implemented a punctuation stripping function yet.