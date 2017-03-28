---
layout: post
title:  "Procedural Ruby"
date:   2017-03-28 19:26:21 +0000
---


So you've started learning to code with Ruby. That's great!

Ruby is an object-oriented language. That is, you assign value to objects, and call on them by defining methods in your code.

For instance, if you want to figure ask somone how many ice cream cones they've eaten, you could define a method, "ice cream," and assign a value to it, "cones." It might look something like this:

def ice_cream(cones)
puts "How many cones have you eaten?"
gets cones.chomp
puts "You have eaten #{cones} cones."
end

"Cones" here is an object, something you're trying to discover a solution to.

The procedure part involves defining and calling a series of methods in a logical order in order to create a program that will find a solution to a query.

Order of operations is important, and the more refined the method, the more exact the results. Think of it as a sandwich. Like math, larger concepts and statements are the bread, with the smaller, finer points of code filling out the inside. Don't forget, in order to get a method to pass, and not break your script, it is necessary to close each function or method that you have created.

One of the trickiest things I find about Ruby is knowing what to add to a method to get it to pass. I tend to make my code more complicated, with too many ifs and elses. But the more simple you can make a statement, the better! It will also help to make any placement changes or name adjustments in the future, especially when you have long lines of code and need to make one minor change.

Ruby was written to be user-friendly: it is readable and sentence-like, and different programmers can write in varying degrees of complexity and still get the same results. If you find yourself overthinking it too much, step away for a while and come back thinking of a new way to write it. It might work better!
