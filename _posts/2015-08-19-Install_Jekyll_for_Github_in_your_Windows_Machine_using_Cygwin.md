---
layout: post
published: true
resource_folder: 'post'
type: 'Blog'
subject: 'Install Jekyll for Github in your Windows Machine using Cygwin'
title: 'Install Jekyll for Github in your Windows Machine using Cygwin'
category: 'LeeL Blog'
image: 'post_web_development.jpg'
author: 'Rogerio dos Santos'
---



Introduction
==============


***Github pages*** uses ***Jekyll*** blog engine on its server. You can have the same ***Jekyll*** blog engine with similar Github configuration running from your computer. This can be useful if you are working on the style of your site that will be in the hosted on Github since you can identify the changes you made faster than upload the new source code on Github and wait for the blog engine running on Github to reload. Another usage would be if you would like to host your own Blog server with similar features than Github from a Windows machine.


This article describes simple procedures that will allow you to build your ***Jekyll*** blog engine environment in a Windows machine using Cygwin or directly into a Linux machine.


Procedure
==============



If you are on Windows, donwload and install ***cygwin***  for windows:
 
[https://cygwin.com/install.html](https://cygwin.com/install.html "Cygwin installation instructions")
 
On ***cygwin*** or ***Linux Machine*** install ***Jekyll***, ***Jimoji*** and ***Site Map***:


> gem install jekyll
> 
> gem install jimoji
> 
> gem install jekyll-sitemap

> 


Now you are ready to use the ***Jekyll*** engine.


Go to the path of your WebSite and execute the following command:


> [Jekyll installation directory]/bin/jekyll serve --watch


The *watch* parameter informs the ***Jekyll*** engine to rebuild the site as soon it detects changes




