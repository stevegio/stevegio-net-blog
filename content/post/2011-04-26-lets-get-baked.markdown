---
author: stevegio
comments: true
date: 2011-04-26 17:32:29+00:00
layout: post
slug: lets-get-baked
title: Let's Get Baked
wordpress_id: 106
categories:
- tech
---

There was a lot of talk on the Interwebs about baked vs non-baked blogging platforms. To summarize, a "baked" blogging system renders all content to static HTML and moves that content to a plain old HTTP server.  The alternative is to have a blogging system that renders a dynamic page for every request.  The advantages of the former is that nothing serves up faster than static HTML files.  It will keep you site from getting [slashdotted](http://en.wikipedia.org/wiki/Slashdot_effect) (does that still happen?), [fireballed](http://daringfireball.net/), etc. if you happen to write something interesting that people want to read.
My original blog, [giolist.com](http://giolist.com) was for the longest time a statically hosted site before Google eliminated publishing static HTML using sftp from Blogger. The closest I came to a meltdown was a while ago when I posted [something](http://urblog.giolist.com/2005/05/scott-n-stevehappy-together.html) that [Dave Winer](http://scripting.com) liked and linked to from scripting.com.  Of course because it was all static HTML my site never went down even though it was hosted on a puny Linux box running Apache.  This incarnation of my blog is hosted on [Wordpress.com](http://wordpress.com) and I'm not sure it would handle the traffic if I were to come up with something [profound](http://www.catspictures.net/2009/05/hover-cat-pictures.html). I find myself wanting to go back to a "baked" system partly because of the scalability factor but also because of the simplicity.  Using static HTML doesn't preclude interaction or other dynamic elements. You can still do interesting things with JavaScript includes like twitter badges, or photo streams in the margins of your site, and of course [Disqus](http://disqus.com/) is more than happy to host your comments if you want them.
I've been looking a lot at systems like [Jekyll](https://github.com/mojombo/jekyll) and [Hyde](http://ringce.com/hyde) but I've also been looking at rolling my own blogging system again. A short list of requirements would include:


	
	
  * [Markdown](http://daringfireball.net/projects/markdown/) support

	
  * no database, all posts are generated from files

	
  * no server-side CGI required or exposed to the Internet

	
  * plugin API

	
  * functional but not overly complex templating system

        
  * post on the go from an iOS device

	
  * [Dropbox](http://dropbox.com) integration (although if your file based I think you get this for free)


It's an interesting project I've been thinking about a lot lately. It might just use one of the open source projects as a base, since it's easier to add some of the features to an existing system than starting from scratch building everything.  The templating engine could be a pain and there are lots of good ones out there in many languages. I wrote one ages ago in Perl.  I'm not sure I want to do that again. The idea of writing my own system seems right.  Now if I can only find the time. _*sigh*_






