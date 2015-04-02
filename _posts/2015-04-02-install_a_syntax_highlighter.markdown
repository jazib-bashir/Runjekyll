---
layout: post
title: Install a Syntax Highlighter
date: 2015-04-02 12:47:35
permalink: /syntax
state: syntax
---
<h3>Overview</h3>
Whether you’re using Markdown or HTML, Jekyll makes it easy for you to insert beautiful code blocks into your pages.

By default, Jekyll comes with pygments.rb, which is a syntax highlighter based on Python. To use it on Windows, you’ll need to install Python and some extra tools.

A nice alternative is the Ruby-based Rouge, which is faster and easier to install, but doesn’t support as many languages as Pygments.

Below, you’ll find instructions for both syntax highlighters. Choose the one that best suits your needs. More information can be found on <a href="http://jekyllrb.com/docs/templates/#code-snippet-highlighting">the official Jekyll website.</a>
<h3>Install Rouge</h3>
Quick and painless: Open your favorite command line tool and enter the following command.
{% highlight ruby %}
	gem install rouge
{% endhighlight %}
Then, in your _config.yml, set Rouge as your syntax highlighter:
{% highlight ruby%}
	highlighter: rouge
{% endhighlight%}
Done!

<h3>Make Pygments work</h3>
If you want to use Pygments, which is a default Jekyll dependency, for syntax highlighting on Windows, you need to install Python, pip and finally the Python base of pygments.rb.

Note: After you complete the following steps, Jekyll might still output errors when building or serving sites. These shouldn’t cause any real problems though, so you can safely ignore them.

<h3>Install Python</h3>
The latest working version of Python at the time of writing is v2.7.8. Python 3 will not work.

Click the button below and download the v2.7 installer that matches your system’s architecture (32bits / 64bits).<br><br>
<a class=" col-md-6 col-md-offset-3 btn btn-default" href="https://www.python.org/downloads/" target="_blank">Get Python</a><br><br>
Execute the downloaded file and go through the steps of the installation.

When you get to the screen below, make sure to click on the box next to Add python.exe to Path and select “Entire feature will be installed on local hard drive.”

<div class="text-center">
	<img src="{{ site.baseurl }}/images/python-path.png">
</div>

<h3>Install pip</h3>
Pip is a tool for installing and managing Python packages, similar to Ruby Gems. You’ll need it to install Pygments, the Python package that pygments.rb uses to highlight your code.

First, click on the button below and download get-pip.py via the link on that site.<br><br>
<a class=" col-md-6 col-md-offset-3 btn btn-default" href="https://pip.pypa.io/en/latest/installing.html" target="_blank">Get pip</a><br><br>
Next, open your favorite command line tool and navigate to the location of get-pip.py on your computer (e.g., C:\pip\ or whatever folder you saved it into).
{% highlight bash%}
	cd C:\pip
{% endhighlight %}
Then, run the following command to automagically download and install all required components.
{% highlight python %}
	python get-pip.py
{% endhighlight %}
<h3>Install Python base of Pygments</h3>
From the command line, run the following command to install the Python base of Pygments.
{% highlight python %}
	python -m pip install Pygments
{% endhighlight %}
<h3>Set Pygments as your syntax highlighter</h3>
If it’s not set already, add the following to your _config.yml to set Pygments as your syntax highlighter.
{% highlight ruby %}
	highlighter: pygments
{% endhighlight %}