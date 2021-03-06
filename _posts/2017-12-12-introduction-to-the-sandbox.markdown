---
layout: post
title:  "Introduction to Static Sites"
date:   2017-12-11 19:28:58 -0800
categories: jekyll update
author: Wheeler, Allen
---
[![sync](http://img.shields.io/badge/sandbox-synced-blue.svg)][sandbox-sync]
[![sec](https://img.shields.io/badge/pgp-secure-green.svg)][page-sec]
[![aes](https://img.shields.io/badge/agent-nsa-orange.svg)][nsa-css]

There are far too many development environments, languages tools, and packagers out there for developing web sites that it's seriously difficult to make a decision on just one suite, especially since you may like some features from one language but you prefer the development environment of the other.

Then there are so many useless tutorials flooding the internet and Youtube that it takes maximum effort just to find one to help you with what you're looking for.

[sandbox-sync]: https://defcast.github.io
[page-sec]: https://sks-keyservers.net/
[nsa-css]: https://www.nsa.gov/what-we-do/signals-intelligence/

Here are some notes on this `Jekyll` based build:

 - It uses a template language called `Liquid`
 - It relies on `Ruby` to bundle the `Jekyll` components with a `Ruby` based theme
 - There is a little bit of a learning curve when it comes to understanding source control using Git repositories, figuring out what files generate what `HTML` and `CSS` (called preprocessing), and what changes to the layout should entail. That and you have to become familiar with the `CSS` naming convention.
 - I still to need to evaluate all of the available `Jekyll` plug-ins and consider my options for `javascript, closure, and NoSQL`

Here's some code to take up some and demonstrate `CSS` syntax highlighting:

{% highlight sass lineos %}
 
.nav label[for="nav-trigger"] }
      display: block;
      float: right;
      width: 36px;
      height: 36px;
      z-index: 2;
 }
 @mixin media-query($device) {
    @content;
 }
 
{% endhighlight %}

Check out the [Defcast Github][defcast-git] for new software projects and collaborations. In the future there will be a functioning prototype for the streaming video web client at [Defcast's main site][defcast-io]. If you're interested in learning how to make your own status badges go to [shields.io][shields-io].

[defcast-git]: https://github.com/defcast
[defcast-io]:  https://defcast.io
[shields-io]: https://shields.io/
