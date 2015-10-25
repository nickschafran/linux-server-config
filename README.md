#Linux Server Config

##About:
This repository (will contain) instructions for accessing a linux server I have configured for hosting web apps, along with a walkthrough, and URL to the application I deploy with it. It is a submission for Project 5 in [Udacity’s Full Stack Web Developer Nanodegree](https://www.udacity.com/course/full-stack-web-developer-nanodegree--nd004).

##To Access
* IP Address:
* SSH:
* URL:

##Software Installed & Configuration
* Create a new user named grader: `sudo adduser grader`
* Give the grader the persmission to sudo:
* Update all currently installed packages:
* Change the SSH port from 22 to 2200:
* Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123)
* Configure the local timezone to UTC
* Install and configure Apache to serve a Python mod _ wsgi application.
* Install and configure PostgreSQL
..-Do not allow remote connections
..-Create a new user named catalog that has limited permissions to your catalog application database
* Install git, clone and setup Catalog App project so that it functions correctly when visiting server's IP address in a browser.

##References:
* Course materials for Udacity's [Configuring Linux Web Servers](https://www.udacity.com/course/configuring-linux-web-servers--ud299).

