---
layout: post
title:  One Thing I Didn't Understand When I Started Learning Ruby
date:   2017-05-26 21:08:22 +0000
---


Sometimes things click. Sometimes they don't.

<iframe src="https://giphy.com/embed/Dg4bJOS0OpyzC" width="480" height="362" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

When I started going through my first Ruby lessons, there were one thing I didn't understand that tripped up *many* of my labs.

`Return`

The lab instructions say to "return true or false," so my code should look like this, right?

```
def my_method(arg)
  if my_array.include?(arg)
	  return true
	else
	  return false
```

<iframe src="https://giphy.com/embed/6Q2KA5ly49368" width="480" height="339" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

But the instructions say "return," I'm so confused!

If I don't use `return` how do I return something? By writing nothing. 

What?!? Replace `return` in your code with nothing.

```
def my_method(arg)
  if my_array.include?(arg)
	  true
	else
	  false
```

Implicit returns! Simple enough to be confusing.

<iframe src="https://giphy.com/embed/An95xQZRS1B1S" width="480" height="336" frameBorder="0" class="giphy-embed" allowFullScreen></iframe>

[The Ruby Style Guide - `return`](https://github.com/bbatsov/ruby-style-guide#no-explicit-return)


