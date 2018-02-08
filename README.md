# Linux-Server-Configuration

* IP Address: 34.215.177.205

* URL: http://ec2-34-215-177-205.us-west-2.compute.amazonaws.com/

* Port: 2200

* Summary of software installed:
Apache2 Server
Postgresql

## Summary of Configurations:
* Update all currently installed packages.
* Change the SSH port from 22 to 2200
* Configure the Uncomplicated Firewall (UFW) to only allow incoming connections for SSH (port 2200), HTTP (port 80), and NTP (port 123).
* Create a new user account named grader.
* Give grader the permission to sudo.
* Create an SSH key pair for grader using the ssh-keygen tool.
* Configure the local timezone to UTC.
* Install and configure Apache to serve a Python mod_wsgi application.
* Install and configure PostgreSQL.
* Clone and setup your Item Catalog project from the Github repository you created earlier.
* Set it up in your server so that it functions correctly when visiting your server’s IP address in a browser.
