GIT Overview
============

*An introduction to GIT in the Warren environment and practial examples to make life simplier!

Table of Contents
-----------------
* Introduction to GIT
* How does Warren utilize GIT?
* Maintaining GIT Repositories
* Other applications for GIT



Maintaining GIT Repositories
----------------------------
GIT first and foremost is a command line environment. Tools exist, such as Windows GITHub which provide a graphical interface for these commands, but GIT in its native form is CLI.
All GIT commands begin with the following command:
    
    git [command]

You can run this command from any directory on a Warren Linux server. However, we recommend only running scripts from the web root directory. (In most cases, this is /srv/www/htdocs)

So to get things off on the right foot, we'll start from the beginning so that you have a better understanding on how cloning, pulling, and merging works when dealing with GIT repositories.

Let's say you've just created a new repository named "HelloWorld".
In order to run this repository on a Warren web server, you'll need to CLONE it first.
To do this, simply type the following command:

    git clone [repository]
*If you created this respository under the Warren company in GITHub, the command will be:

    git clone https://github.com/WarrenDistribution/[repository].git
*So, using our example, the command would look like:
  
    git clone https://github.com/WarrenDistribution/HelloWorld.git
    
