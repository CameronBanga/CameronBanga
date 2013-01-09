---
layout: post
title: "Powered by Octopress"
date: 2013-01-08 22:23
comments: true
categories: 
---
If you're perusing around the new blog, you may have noticing the short credit line in the footer. This new blog is being powered by [Octopress](http://octopress.org), which I would almost guarantee you haven't heard about. Here's a short description from [the project's webpage](http://octopress.org).

>Octopress is a framework designed by [Brandon Mathis](http://brandonmathis.com/) for [Jekyll](http://github.com/mojombo/jekyll), the blog aware static site generator powering [Github Pages](http://pages.github.com/). [Simply clone or fork Octopress](https://github.com/imathis/octopress), install dependencies and the theme, and you’re set.

If the paragraph above contains a lot of words that scare you, don't worry or leave this page, it's not *that* bad, I promise. Let's take a look at a quick pro/con list for Octopress.

**Pros**
* It's lightweight and self-sufficient
* A variety of affordable/free hosting options
* I can write in [Markdown](http://daringfireball.net/projects/markdown/)
* Clean, attractive, and customizable
* Writing posts, updating posts and pushing blog changes is quick and easy and done completely in my desktop

**Cons**
* It's a bit of a bitch to set up
* It's lightweight and self-sufficient

So why Octopress instead of another solution like Wordpress, Tumblr, Blogger, etc? I've used a good deal of these solutions and easily could have set one up for the Smallest Pixel. But I didn't for a variety of reasons.

First and foremost, this blog is an experiment for me, as I wanted a bit of a technical challenge. I'm using a lot of technologies here that I've never really used before, so this is very much me stepping outside of my comfort zone. 

To run this blog, I require Terminal.app, some simple UNIX commands, Git, GitHub and Markdown. I've never used any of these technologies extensively in the past, so this blog is a real adventure as I write my first few posts.

Because I'm using all of these technologies, I'm not relying upon a free web start-up that I'm not certain will be around in six months, and that's a big deal to me. With other services, I'm completely at the mercy of the provider. Want to export all of my posts? Better hope they have a service for that. Need to make a change to the site template or a page component I don't like? Here's a crummy [WYSIWYG](http://lmgtfy.com/?q=WYSIWYG) editor.

Octopress is completely self-contained, sitting on my MacBook Pro contained in a 4.7 MB folder. That's right, this entire site sits duplicated on my computer in only 4.7 MB. 

Most importantly, this means that all of my blog posts are available to me at anytime in [Markdown](http://daringfireball.net/projects/markdown/) format. If you're unfamiliar with Markdown, it is a language written by [John Gruber](http://daringfireball.com) that is designed to be an easy-to-read and easy-to-write format for bloggers. 

I write in plain text, using simple characters such as [,},(,),* or > to implement common formatting that would typically require HTML. This means that I don't need messy WYSIWYG editor and my posts are easy to read, and then easily converted to static HTML pages via Octopress. Because of this, I can write in my preferred desktop app (I use [iA Writer](http://google.com)), and then have that Markdown file published up to the server.

The magic of Octopress is that once I write, I only need to connect my blog to a hosting provider. I used [GitHub](http://github.com) using their free personal page service, but I could have gone with [Heroku](http://heroku.com) or even hosted my own solution. This is great because I have a variety of free options, but can fall back on my own hosting plan if need be. Once I've selected a host, I just set up a Git repository on my Mac, throw a few simple commands into Terminal.app, and everything is published. I never have to leave my desktop.

This writing setup isn't perfect though, and may not exactly be for everyone. First and foremost, it's a bit of a technical set up. I had to update Ruby on my Mac, set up a Git repository, clone a remote repository, push, pull, etc. You need to at least understand some basic premises of the command line and also understand Git management through Terminal.app in order to probably get Octopress set up. 

That being said, Octopress has fantastic documentation and I'm by no means a Terminal expert. In fact, I had just started using Git through the command line less than a week before I started working on the installation progress. I had some Ruby issues, but once I solved those, the entire Octopress installation process took about an hour. 

When I mentioned that Octopress is a bitch to set up though, remember that I'm not a programmer by any means, and even I could get it set up. The tag-line for the project is "A blogging platform for hackers" and while I like to fiddle and play around, I am not proficient with most of the technologies needed here and even I was able to survive using the guides.

Another downside to Octopress is that, because it's lightweight and self-sufficient, you won't find a variety of pre-made and readily available themes or plugins like you would for Tumblr, Blogger or Wordpress. You need to be comfortable editing some HTML and CSS, or you're going to be stuck with the default theme. It's an attractive theme, but if you want something custom, you're going to have a rough time.

So far, I'm in love with Octopress and would recommend it to anyone who has a beginners level of understanding of using Git in Terminal.app. It's an amazing blog platform and I'm really excited to use it here over the next few months. If you have any questions on using it yourself, [feel free to email me](mailto:cameron@cameronbanga.com)!
 
