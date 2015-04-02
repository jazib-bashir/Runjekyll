---
layout: post
title: Install the Jekyll Gem
date: 2015-03-31 14:41:29
permalink: /jekyll
state: jekyll
---
<h3>Installation</h3>
Jekyll itself comes in the form of a Ruby Gem, which is an easy-to-install software package. To install Jekyll and all its default dependencies, launch your favorite command line tool and enter the following command.
{% highlight ruby %}
	gem install jekyll
{% endhighlight %}
Hit enter, watch, enjoy. This might take a while due to the number of dependencies.
<h3>Compatibility</h3>
The latest version of Jekyll at the time of writing is v2.4.0, which is compatible with Windows. Most of the previous versions are, too. Do not attempt to install Jekyll v1.4.3, <a href="https://github.com/jekyll/jekyll/issues/1948">though, which is known to be incompatible with Windows.</a>

Check back here when a new version of Jekyll is released to find out if it remains compatible with Windows.
<h3>Summary</h3>
You have successfully installed Jekyll. In fact, you can already build and serve sites without errors, unless there are blocks of code in there and you want to use syntax highlighting. To find out how to properly set up one of two syntax highlighters, click on the button below.<br><br>
<a class=" col-md-6 col-md-offset-3 btn btn-default" href="/Runjekyll/syntax">Syntax Highlighter>></a><br><br>