---
layout: post
published: true
resource_folder: 'post'
type: 'Blog'
subject: 'Linux - Disable Sleep'
title: 'Linux - Disable Sleep'
category: 'LeeL Blog'
image: 'post_knowledge.jpg'
author: 'Rogerio dos Santos'
---



To disable the option of your device turn off the monitor and go to sleep after an amount of time, you can follow the steps below:


Edit the "/etc/lightdm/lightdm.conf"  file adding the following lines to the [SeatDefaults] section:


     # don't sleep the screen
     xserver-command=X -s 0 dpms


Tip: To edit the file you can use the nano software by typing the following on the linux terminal:


     sudo nano /etc/lightdm/lightdm.conf


Note: This solution was tested with Raspberry Pi




