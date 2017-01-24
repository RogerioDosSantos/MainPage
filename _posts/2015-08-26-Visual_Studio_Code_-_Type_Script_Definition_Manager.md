---
layout: post
published: true
resource_folder: 'post'
type: 'Blog'
subject: 'Visual Studio Code - Type Script Definition Manager'
title: 'Visual Studio Code - Type Script Definition Manager'
category: 'LeeL Blog'
image: 'post_web_development.jpg'
author: 'Rogerio dos Santos'
---




The Type script definition manager allow you to install intellisense definitions that can be used on editors that support TypeScript (E.g.: Visual Studio Code) to get intellisense of complex languages framework (E.g.: AnngularJS).


The example below shows how to use it to get AngularJS intellisense on Visual Studio Code


Type script definition manager installation


    npm install -g tsd


Local Initialization - From the folder the folder where the definition should be run


    tsd init
  
IntelliSense for the Angular Module and Services


    tsd query angular --action install --save


On your code (E.g.: controller.js) link the reference to the **tsd.d.ts** file that will contain all the installed intellisense references


    /// <reference path="your_path/angular.d.ts" />


Now you have intellisense for AngularJS!


