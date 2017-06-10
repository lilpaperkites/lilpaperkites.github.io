---
layout: post
title:  "Asset Pipeline"
date:   2017-06-10 04:01:55 +0000
---


The asset pipeline is the means by which assets, as in JavaScript and CSS files, images, videos, etc, are processed by your browser. It is a framework in Ruby on Rails that allows assets to be combined with assets from other Ruby gems.

It combines multiple JavaScript assets into a single JS file and compresses them in a process known as concatenation, then removes extra spaces and comments in the code, thereby minimizing the amount of HTTP requests and thus the load time for web applications.

Additionally, the asset pipeline can pre-process assets written in other languages before they are sent to a browser to decrease load time.

So, if you have a bunch of disparate assets calling on different filenames with varying degrees of redundancy, they can all show up in the browser under a singular URL, even if the assets are moved around. It's a pretty neat tool for multi-dimensional web applications.
