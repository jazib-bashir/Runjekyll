---
layout: post
title: Install Ruby and the Ruby DevKit
date: 2015-03-30 14:15:31
permalink: /ruby
state: ruby
---
Ruby is the programming language that Jekyll is written in. You’ll need to install Ruby and the corresponding DevKit, which is needed to build some of Jekyll’s dependencies as “native extensions”.
<h3>Install Ruby</h3>
First, click on the button below and download the installer for Ruby v2.0.0 that matches your system’s architecture (x86 / x64).<br><br>
<a class=" col-md-6 col-md-offset-3 btn btn-default" href="http://rubyinstaller.org/downloads/" target="_blank">Get Ruby for Windows</a><br><br>
Execute the installer and go through the steps of the installation. When you get to the screen below, make sure to check the “Add Ruby executables to your PATH” box.
<div class="text-center">
	<img src="{{ site.baseurl }}/images/ruby-path.png"><br><br>
Click Install and Ruby will be installed within seconds.
</div>
<h3>Install the Ruby DevKit</h3>
Jekyll has some dependencies which, out of the box, only provide raw source code. To make them into fully functional executables, you’ll probably need to install the Development Kit.

Click the button below and download the DevKit archive that corresponds to your Ruby installation and system architecture. For Ruby v2.0.0, the file name will begin with DevKit-mingw64. Choose the 32bits or 64bits version depending on your system.<br><br>
<a class=" col-md-6 col-md-offset-3 btn btn-default" href="http://rubyinstaller.org/downloads/" target="_blank">Get the Ruby Devkit</a><br><br>

Next, you need to initialize the DevKit and bind it to your Ruby installation. Open your favorite command line tool and navigate to the folder you extracted the DevKit into.
{% highlight bash %}
	cd C:\RubyDevKit
{% endhighlight %}
Auto-detect Ruby installations and add them to a configuration file for the next step.
{% highlight ruby %}
	ruby dk.rb init
{% endhighlight %}
Install the DevKit, binding it to your Ruby installation.
{% highlight ruby %}
	ruby dk.rb install
{% endhighlight %}