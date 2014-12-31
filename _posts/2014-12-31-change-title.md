---
layout: post
title: how do i change the title and get away from the "awesome" template?
date: 2014-12-31 14:30:00
categories: blog
---
apparently the title lives in _config.yml

also i picked up on the daring fireball site that you do blockquotes with this symbol: > and with > you don't need to add the white space (extra empty line between lines to have paragraphs) so here goes--config looks like this and i guess you just change the content? 

># Site settings

>title: Your awesome title

>email: your-email@domain.com

>description: > # this means to ignore newlines until "baseurl:"
  Write an awesome description for your new site here. You can edit this

>  line in _config.yml. It will appear in your document head meta (for

>  Google search results) and in your feed.xml site description.

>baseurl: "" # the subpath of your site, e.g. /blog/
url: "http://yourdomain.com" # the base hostname & protocol for your site

>twitter_username: jekyllrb

>github_username:  jekyll

># Build settings

>markdown: kramdown

--

Update: Once you make your changes in the config file, you save. but it doesn't show up when you refresh the local host! apparently you have to go back to the terminal and hit "ctrl+C" then the "up" arrow so that "jekyll serve" shows up and you hit enter--i guess refreshing the whole site backend since you messed with config..then you hit refresh on your localhost and it works! 

hello world, i'm vivian and i have no idea what i'm doing..and am trying to change that, slowly.