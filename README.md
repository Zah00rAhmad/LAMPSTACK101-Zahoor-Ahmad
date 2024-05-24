# LAMPSTACK101-Zahoor-Ahmad
This is my first project on GitHub
Introduction:
The LAMP stack is a popular open-source web development platform that consists of four main components: Linux, Apache, MySQL, and PHP (or sometimes Perl or Python). This documentation outlines the setup, configuration, and usage of the LAMP stack.

Step 0: Prerequisites 
EC2 Instance of t2.micro type and Ubuntu 24.04 LTS (HVM) was lunched in the us-east-1 region using the AWS console

Step 1
The security group was configured with the following inbound rules:
Allow traffic on port 80 (HTTP) with source from anywhere on the internet.
Allow traffic on port 443 (HTTPS) with source from anywhere on the internet.
Allow traffic on port 22 (SSH) with source from any IP address. This is opened by default.

Step 2
Connect our instance using SSH, then cd into the folder where the private-key was downloaded then ssh into it
cd desktop
chmod 400 steghub.pem
ssh -i "steghub.pem" ubuntu@ec2-34-227-7-216.compute-1.amazonaws.com

Step 3 - Install Apache and Update the Firewall
Run apache2 package installation
Enable and verify that apache is running on as a service on the OS.
The server is running and can be accessed locally in the ubuntu shell by running the command below:
Test with the public IP address if the Apache HTTP server can respond to request from the internet using the url on a browser.

Step 4 - Install MySQL
Install a relational database (RDB)
Log in to mysql console

Step 5 - Install PHP
Install php Apache is installed to serve the content and MySQL is installed to store and manage data. PHP is the component of the set up that processes code to display dynamic content to the end user.

Step 6 - Create a virtual host for the website using Apache

Step 7 - Enable PHP on the website

Step 8 — Testing Database Connection

Understanding the basis of DevOps
What is Software Development Life Cycle?
The software development lifecycle (SDLC) is the cost-effective and time-efficient process that development teams use to design and build high-quality software. The goal of SDLC is to minimize project risks through forward planning so that software meets customer expectations during production and beyond.

Understanding LAMP STACK
The LAMP stack is a popular open source software stack for building and deploying web applications. LAMP is an acronym for the components in the stack: Linux (operating system), Apache (HTTP server), MySQL (database) and PHP, Perl or Python (programming language). It is Stable, Simple, Powerful—these are words most often used to describe LAMP.

Uderstanding Chown & Chmod Linux Command
Use the chown command to change file owner and group information. We run the chmod command command to change file access permissions such as read (r), write (w), and execute (x) permission.

What TCP & UDP is
Transmission Control Protocol (TCP) and User Datagram Protocol (UDP) both are protocols of the Transport Layer.

Cick here to Practise basic text editing with Vim
Assignment LAMP STACK project
Prerequisites
AWS Account
Launch EC2 with Ubuntu
Setup a LAMP Stack on Ubuntu
Install Apache & Update Firewall
Install MySQL Database
Install PHP
Setup Virtual Webhost
Test PHP Processing
Test Database Connection
