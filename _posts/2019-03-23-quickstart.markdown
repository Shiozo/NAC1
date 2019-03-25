---
layout: post
title:  "Quickstart"
date:   2019-03-23 16:20:42 -0300
categories: jekyll update
author: Claudio Shiozo
---

Jekyll is a simple, extendable, static site generator. You give it text written in your favorite markup language and it churns through layouts to create a static website. Throughout that process you can tweak how you want the site URLs to look, what data gets displayed in the layout, and more.

<h2>Instructions</h2>

- Install a full Ruby `development environment`

- Install Jekyll and `bundler gems`
{% highlight ruby %}
gem install jekyll bundler
{% endhighlight %}

- Create a new Jekyll site at  `./myblog`
{% highlight ruby %}
jekyll new myblog
{% endhighlight %}

- Change into your new directory
{% highlight ruby %}
cd myblog
{% endhighlight %}

- Build the site and make it available on a local server
{% highlight ruby %}
bundle exec jekyll serve
{% endhighlight %}

- Now browse to `http://localhost:4000`

If you encounter any unexpected errors during the above, please refer to the troubleshooting page or the already-mentioned requirements page, as you might be missing development headers or other prerequisites.