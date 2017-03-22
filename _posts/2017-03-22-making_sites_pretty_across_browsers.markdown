---
layout: post
title:  "Making Sites Pretty Across Browsers"
date:   2017-03-22 00:32:57 -0400
---


I just finished up my HTML/CSS portion of the Online Developer Program. As a former Project Manager, it was eye-opening to see it from the development side. Since helping out with some QA in the last couple years, I've been interested in how you can get your site to render well across various browsers. So, I've collected some tips. These tips were compiled from my learnings in the Online Developer Program and various Google searches. Hopefully, I am not sharing outdated information (if so, [tweet me](https://twitter.com/daniellecroxton)). 

* Declare your [doctype](https://www.w3schools.com/tags/tag_doctype.asp)
* Validate your [HTML](https://validator.w3.org/) & [CSS](https://jigsaw.w3.org/css-validator/)
* Use feature/behavior detection like [Normalize](http://nicolasgallagher.com/about-normalize-css/) or [Modernize](https://modernizr.com/) in your code
* Test across multiple browsers with [testing tools](http://mashable.com/2014/02/26/browser-testing-tools/#Qw6vvOQKsuqp)
* Check your site visitor's browser preferences and prioritize the top browsers for manual testing and fixing (global stats can be found [here](https://www.w3counter.com/globalstats.php))
* Use the CSS box model with the [`box-sizing` property](https://css-tricks.com/box-sizing/)
* Understand [CSS measurment ](http://thenewcode.com/775/Which-CSS-Measurements-To-Use-When)options
* Use [clearfix](https://css-tricks.com/snippets/css/clear-fix/)
* If you need to make tweaks for old versions of IE, try [conditional comments](https://msdn.microsoft.com/en-us/library/ms537512)
