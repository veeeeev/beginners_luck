---
layout: post
title: practicing with permalinks
date: 2015-01-03 18:37:00
categories: blog
---
am not really sure how to "practice" permalinks other than I guess writing links using the format...then hoping that it works when the domain name changes at some point in the future? A is cooking so I have to look busy. Yes I know he will see this later.

hokay. so, I guess the way this makes the most sense is if I write an index of my previous links to practice writing permalinks to other posts and page (since I only have 1 other page right now..) 

About is {{site.baseurl}}/about <--does not result in link. html turns it into "/about"

"{{site.baseurl}}" is not anything when running locally. you need to make a link out of the text...which means that we need to revert to the original link insertion format from [my post on markdown syntax]({{site.baseurl}}/syntax-2.html) "\[text\]\(url\)" (remember you need \ to escape the punctuation used even when trying to spell out the code) with the curly brace baseurl as part of the URL. 

[About]({{site.baseurl}}/about)

-- i thought i would be clever and try to write the same syntax that worked for the above "About" link and link the text to my post on markdown syntax, but if you click it, you will see that it gives you an error. this is apparently because you need to give them the url it is LOCALLY instead of online. 

trial: [my post on markdown syntax]({{site.baseurl}}/posts/2015-01-02-markdown-2.md) <--when trying this trial, I was talking A through my thought process and it became clear that this computer I'm working on now does not have the post I want to link to, locally! So we had to go to Sourcetree and "Fetch" all the commits I'd done in the last two days from the other computer.

Quick recap from my overview on git terminology with A:

* When starting the project on one computer, all the versions of the project were local and I had to push all commits to "origin"/remote for live.

* When I worked on the project on a different computer, I created a second local branch that in turn pushed the versions from there to origin. These new versions from the second local branch only existed on local II and origin.

* Picking up the project on my original computer at home (aka local I), I only had commits up to when I last worked on this local repository.

* To continue working, I need to fetch all the latest commits from origin to local I and rebase my current work on origin/gh-pages. 

So, to keep it unconfusing to Git, I commit my current work (this post) without pushing. Then you right click on the thing you want to rebase on (you want to rebase current changes to the origin, so right click on the last commit that you want your current changes to be implemented on), and the branches combine.

Now A is saying another practice method is to make 2 new pages and make them link to each other. 

He says I keep quoting him..but I only think it's fair to cite the times I am helped and give him credit/be honest about my roadblocks.