---
layout: post
title: "adding images"
date: 2015-01-06 17:21:00
categories: blog
---
so since we can't do style yet (A says to "master" formatting first)--it is very hard to not jump the gun--i've been given an assignment: to embed an image from another site. 

not just an image. a gif!

okay..finally found info about images in the jekyll page on writing posts

it says you need to make a folder called assets or downloads. 

base assumption is that you would need to find a file then save it into the folder structure

so the thing says this as a sample: \!\[My helpful screenshot\]\(\{\{ site.url \}\}/assets/screenshot.jpg\)

testing: [Shiba-Ram!]({{site.url}}/assets/shibaram.jpg)

--

update: boo it doesn't work locally...is it because the IMAGE NEEDS TO BE COMMITTED??

committed shibaram.jpg and pushed it...now trying code again..

testing: [Shiba-Ram!]({{site.url}}/assets/shibaram.jpg)

--

update: doesn't work.. :( back to the drawing board..

![ShibaRam]({{site.url}}/assets/shibaram.jpg)

![ShibaRam]({{site.url}}/_assets/shibaram.jpg)

![ShibaRam]({{site.baseurl}}/assets/shibaram.jpg)

![ShibaRam]({{site.baseurl}}/_assets/shibaram.jpg)

--

nope still doesn't work. just had A check my code and apparently what I've been trying to do is host the image on my own site and point at it...when he meant to just point at an image. 

![ShibaRam](https://i.imgur.com/eW6LMB6.jpg)

Easy. 

Not what I thought he meant...