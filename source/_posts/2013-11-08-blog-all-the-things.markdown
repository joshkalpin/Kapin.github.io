---
layout: post
title: "Blog All the Things!"
date: 2013-11-08 22:54
comments: true
categories:
---

Well this is a long time coming to say the least. I've kept saying that I'm going to build my website since I started
at UW and well it is finally here.

This website is built with the magic that is known as [Octopress](http://octopress.org) using the awesome [Octoflat](https://github.com/alexgaribay/octoflat) theme.
I've tweaked a few things from the default theme and will hopefully change the colours around in the future to be a little less bright, but I'm incredibly happy that it is finally done.

## Why Octopress?

First, I didn't want to deal with the pain of setting up a hosting server to run a simple website. Octopress is built on top of Jekyll, a static page generator.
This allows me to write everything here in markdown, which is then converted into HTML when I deploy. Speaking of deploying, it is just as simple.

{% codeblock Deploying Octopress %}
rake generate
rake deploy
{% endcodeblock %}

Lastly, the big thing that drew me to it was the vast array of themes and plugins. I'm not a designer nor do I really enjoy digging around in vast piles of HTML and CSS to create a website from scratch.
Having some awesome third party themes made it easy to start with someone's awesome template and tweak it to my liking (as seen here).

I'll keep it short for now but I'm glad I finally got this monkey off my back.
