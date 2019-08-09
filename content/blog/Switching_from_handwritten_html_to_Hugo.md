---
title: "Switching from handwritten html to Hugo"
date: 2019-08-09T12:10:49Z
tags: ["web"]
draft: false
---

For a while this site ran using handwritten html with a few lines of php to include partial files
with php-fpm, and it worked well enough.

However dynamically generating pages every request for a static site is obviously pointless and
only adds another layer of complexity and a (slight) risk for security issues.

<br>

So we decide to try [hugo](https://github.com/gohugoio/hugo). After an hour flipping through the
docs we were ready to port the site, which was surprisingly easy and seems capable of almost
exactly what we wanted; only professional instead of the inevitable makefile, m4, & Perl horror
I would have ended up with making it myself. 

Almost everything was able to be directly ported only having to swap out a few lines, and was
left with many times the functionality, such as the blog this is now posted to, although it
still could use a decent amount of cleanup. 
