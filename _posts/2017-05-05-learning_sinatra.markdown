---
layout: post
title:  "Learning Sinatra"
date:   2017-05-05 13:39:22 +0000
---


Sinatra is a framework library of a series of classes used for coding web programs in Ruby. It is a gem that you can install and "require" in a Ruby script to aid in app development.

Sinatra uses URL routes to respond to respond to HTTP request methods. It will return the block of code you've programmed in it to the web browser.

It is more flexible and simple than other domain-specific languages, making your Ruby coding cleaner and shorter. It uses a minor amount of memory, and returns requests quickly.

Its simplicity is commonly explained thus:

Instead of defining a method and putsing what you want to print to the terminal like so

> def say_hi
> puts "Hello World!"
> end

you can simply type

> require "sinatra"
> get("/") { "Hello World!" }

and "Hello World!" will print. It is accessing the "handler," or shortcut code, that exists within Sinatra already to make common tasks more streamlined and less repetitive, making you a more efficient coder.

Sinatra is perfect as an alternative for the heavier domain-specific language, Rails, but can also work alongside (or inside) Rails to create micro apps within larger programs. It's great to know both, but Sinatra is a good starting point for developing smaller or less intense web applications.
