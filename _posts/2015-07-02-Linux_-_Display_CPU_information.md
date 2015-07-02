---
layout: post
published: true
resource_folder: 'post'
type: 'Blog'
subject: 'Linux - Display CPU information'
title: 'Linux - Display CPU information'
category: 'LeeL Blog'
image: 'post_knowledge.jpg'
author: 'Rogerio dos Santos'
---




To know the CPU information can be extremely utile when you want to install a third party software that does not distribute it software using [Personal Package Archives](https://launchpad.net/ubuntu/+ppas) ("PPAs") and therefore to be able to install it using the command "apt-get". 


On those cases, usually the installation process will require you to copy a file to your linux device that should be selected among different processors and distributions information.


The CPU information is located on the "/proc/cpuinfo" file. You can visualize this file content by executing the following command on your Linux Terminal:


     $ more /proc/cpuinfo


Note: This information was tested with Raspberry Pi.




