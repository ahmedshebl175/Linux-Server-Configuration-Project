# Linux Server Configuration Project
## Third Project - Full Stack Web Developer Nanodegree Program - 1MAC - UDACITY
### Project Overview
I will take a baseline installation of a Linux server and prepare it to host my web applications. I will secure my server from a number of attack vectors, install and configure a database server, and deploy one of my existing web applications onto it.

# Pre-requisite:
    -Git Bash(https://git-scm.com/downloads)
    -Amazon Lightsail Account(https://lightsail.aws.amazon.com/)

# Instructions:
    - Start a new Ubuntu Linux server instance on Amazon Lightsail.

### Secure my server
    - Update all currently installed packages.
    - Change the SSH port from 22 to 2200. Make sure to configure the Lightsail firewall to allow it.
    - Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).

### Give grader access.
In order for my project to be reviewed, the grader needs to be able to log in to my server.

    - Create a new user account named grader.
    - Give grader the permission to sudo.
    - Create an SSH key pair for grader using the ssh-keygen tool.

### Prepare to deploy my project.
    - Configure the local timezone to UTC.
    - Install and configure Apache to serve a Python mod_wsgi application.
    - Install and configure PostgreSQL:
    - Create a new database user named catalog that has limited permissions to your catalog application database.
    - Install git.

### Deploy the Item Catalog project.
    - Clone and setup my Item Catalog project from the Github repository I created earlier in this Nanodegree program.
    - Set it up in my server so that it functions correctly when visiting my server’s IP address in a browser. Make sure that my .git directory is not          publicly accessible via a browser!

### Another files:
    - udacity_grader.rsa (To acccess grader user in my server)

# Version:
    - 1.0

# Author:
    - Ahmed Shebl AbdElKader