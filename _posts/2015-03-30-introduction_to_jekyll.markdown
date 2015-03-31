---
layout: post
title: Introduction to Jekyll
date: 2015-03-30 2:03:27
---
<h1>Introduction</h1>

<a href="http://jekyllrb.com">Jekyll</a>, a simple, blog-aware, static site generator, is very easy to set up on Mac OS X or Linux. On Windows, not so much. This site is here to help.

Please note: Using Jekyll on Windows is not officially supported by the Jekyll team. And while this guide is featured on <a href="http://jekyllrb.com/docs/windows/">the Jekyll website</a>, it remains unofficial.

Click the button below to get started and go through the installation process step by step or select a specific step from the sidebar on the left.<br><br>
<a class=" col-md-6 col-md-offset-3 btn btn-default" href="/ruby">Get Started>></a><br><br>
<h2>Versions</h2>
If you follow this guide step by step, you'll end up with the following software versions. These have been tested and work with Jekyll on Windows.

Versions that have been successfully tested in the past are also listed in the third column. It is generally encouraged to keep your Gems updated (up to the versions indicated below) by regularly running. 
{% highlight ruby %}
	gem update && gem cleanup.
{% endhighlight %}
<div class="col-md-8 col-md-offset-2">
<table class="table table-hover table-bordered">
  <tr>
  	<th class="text-center">Software (package)</th>
  	<th class="text-center">Version</th>
  	<th colspan="2" class="text-center">Also Tested</th>
  </tr>
  <tr>
  	<td>Ruby</td>
  	<td>2.0.0p576</td>
  	<td>2.0.0p481</td>
  </tr>
  <tr>
  	<td>Jekyll</td>
  	<td>2.5.1</td>
  	<td>2.4.0 2.3.0 2.2.0 2.1.1 2.1.0</td>
  </tr>
  <tr>
  	<td>Listen</td>
  	<td>2.7.11</td>
  	<td>N/A</td>
  </tr>
  <tr>
  	<td>wdm</td>
  	<td>0.1.0</td>
  	<td>N/A</td>
  </tr>
</table>
</div>
<div class="col-md-8 col-md-offset-2">
<table class="table table-hover table-bordered">
  <tr>
    <th colspan="3" class="text-center">If you use Pygments for syntax highlighting</th>
  </tr>
  <tr>
    <td>pygments.rb</td>
    <td>0.6.0</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td>Python</td>
    <td>2.7.8</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td>pip</td>
    <td>1.5.6</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td>setuptools</td>
    <td>5.4.1</td>
    <td>N/A</td>
  </tr>
  <tr>
    <td>Pygments</td>
    <td>1.6</td>
    <td>N/A</td>
  </tr>
</table>
</div>
<div class="col-md-8 col-md-offset-2">
<table class="table table-hover table-bordered">
  <tr>
    <th colspan="3" class="text-center">If you use Rouge for syntax highlighting</th>
  </tr>
  <tr>
    <td>Rouge</td>
    <td>1.7.3</td>
    <td>1.7.2 1.6.2 1.6.1 1.5.1 1.4.0</td>
  </tr>
</table>
</div>