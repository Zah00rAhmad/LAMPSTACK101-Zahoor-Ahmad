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
Let's Connect our instance using SSH, then cd into the folder where the private-key was downloaded then ssh into it
cd desktop
chmod 400 steghub.pem
ssh -i "steghub.pem" ubuntu@ec2-34-227-7-216.compute-1.amazonaws.com
