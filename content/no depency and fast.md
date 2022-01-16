+++
title = "no javascript and unnecessary css dependency"
date = "2022-01-17"
+++

On the basis of great work of [simple.css](https://github.com/kevquirk/simple.css) and [Nicole White](https://github.com/nicolewhite/nicolewhite.github.io_old), only 10KB css file is needed (2.91KB transfered if you minify it ), no jQuery or Bootstrap at all.

* one html (1.46KB transfered / 1.86KB size)
* one css (3.91KB transfered / 10.42KB size)
* **optional** GitHub/mail/rss icons
* **optional** favicon

In my personal [blog](https://tsai002.github.io), I make these svgs and favicon inlined to html so that only two requests required:

* one html(6 icons included) (5.97KB transfered / 10.05KB size)
* one css (2.91KB transfered / 7.08KB size)

Zola is able to minify html and I minified css manually.