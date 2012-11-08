---
layout: post
author: Robb
description: ""
category: announcements
tags: [jekyll, github]
---
{% include JB/setup %}


## A standard wiki wasn't going to cut it ##

When I had the idea for railsdoc.org, I couldn't figure out how to get
everything I wanted:

* Easy for anyone to edit
* Easy to manage and prevent "edit wars"
* Easy to host
* Inexpensive so long as it's small
* A community site with discussions on every page

[Mediawiki](http://www.mediawiki.org/wiki/MediaWiki) is what Wikipedia
runs on. It's the standard for collaborative web sites. However,
fights over page edits ("edit wars") ruined the Wikipedia editing
experience for me. Further, Wikimedia has a reputation for being a
complex program to administer. I wanted to run Railsdocs.org without
introducing a whole new workload. And so I didn't consider using
Mediawiki.

## Then I remembered Github Pages ##

[Github Pages](http://pages.github.com/) are a way to serve an entire
website out of a [Github Repository](https://github.com/). If you're
new to Github, it's a collaborative backup system used for everything
from private software projects to
[German laws](https://github.com/bundestag/gesetze). 

The cool thing about Github is that the system enables people to
collaborate with vastly less drama than with a wiki. Ok, there may
still be drama, but the *content itself* won't suffer because of it.
Many large and complex projects use Github to coordinate thousands of
contributors.

And Github Pages has
[Jekyll](https://help.github.com/articles/using-jekyll-with-pages).
And Jekyll has [Jekyll Bootstrap](http://jekyllbootstrap.com/).
Putting it all together would give me a wiki w/out the usual problems.


## I added wiki-like features to railsdocs.org ##

I've been adding in the features that makes wikis friendly; and
hooking it all up to Github to do the work. For example, each page has
a familiar-looking button bar. Here's [Tutorials](/pages/tutorials.html):

![Edit Button](/images/unwiki-button-bar-screenshot.png)

The `Edit` button links directly to a Github web editor with the page's text.
If you've already created your free Github account and are logged in,
[this is what you'll see](https://github.com/dogweather/railsdocs.org/edit/gh-pages/pages/tutorials.md):

![Page Editor](/images/edit-window-screenshot.png)

The key difference here compared to a wiki is that the changes aren't
immediately live. There's a publication workflow in place. Clicking
Save will submit the changes to an editor for review. (This is called
"submitting a pull request" in Github lingo.)

This is an ongoing experiment. I'll post again once I've seen it work
a while.



posted by [Robb](http://www.weblaws.org/robb/about), robb@weblaws.org.
