# Continuous Integration with Microsoft Azure cloud

This project was developed for my postgraduate degree. I developed a continuous integration appliaction hosted in Microsoft Azure cloud. This projects consists in creating three VMs (Ubuntu 18.04) that will be used for different purposes. 

First server: LAMP stack - Linux, Apache, MySql and php. This server will host a simple website page that register users. The goal was not to develop a good website but to create integration between the application (LAMP) and the changes made per developers and uploaded to a git server (second server). The changes are uploaded to git which is connected to a Jenkins server (third server).

Jenkins compared the filed and uploads them automatically to the apache server therefore, every change uploaded to git will be seen in the web page that is hosted in Apache.


This project was completed by me and other two members.
