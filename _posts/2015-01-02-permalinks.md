---
layout: post
title: what the hell are permalinks?
date: 2015-01-02 12:13:00
categories: blog
---
A says I should try to figure out how linking between pages works. The only thing I can find on the documentation site says Permalinks, so..what are those? 

A says it looks like we have to link absolutely..but what exactly is the difference....????

Asked A and he says this:

> The difference in links is 
“https://vivianschan.github.io/beginners_luck/article”
vs.
“/beginners_luck/article”

> you want the latter, because then it will always work regardless of where you are hosting

> however, what would be even better is if you can link to “{base_url}/article” so that even if the beginners_luck fragment is changed, it’ll still work

> see if you can figure that out

ohkay...SIGH

---

update

this has been a very frustrating day with permalinks. 

back to the first question i had

# What are permalinks and why do you want to use them?

Permalinks help prevent links from breaking in the case of domain changes. For example, this blog is currently hosted at vivianschan.github.io/beginners_luck. If I were to want to move it to another domain someday, all the internal linkages would break. So instead, you use a permalink to effectively use a variable to anchor the domain section or "vivianschan.github.io" so that when that segment changes, you don't break all the other URL's! Does that make sense? I think I need to sit on it again for a bit..FACT CHECK COMING. 

On variables:

In the words of A: It's like vba: you can either change a number in every place it's used or you can enter it in a cell and use the cell name to refer to it. 