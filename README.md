# FSND-Proj3-Linux-Server-Config
Full Stack Nanodegree final project. Linux Server Configuration

# IMPORTANT NOTE:

Due to issues with the class material in the second section, I was exempted from the second project.
In order to complete the final project, I deployed a substitute app to my configured Ubuntu server.
The deployed app uses flask, an HTML template, css, and queries a PostgresQL database to display a table containing data (specifically the UK Beatles Discography). I used python to create and insert data into the "beatles" table on the posgresql database called "allen".

This simple app demonstrates the proper function of the ubuntu-apache-wsgi-flask-python-posgresql stack.
With this caveat, my project satisfies the rubric. 


## IP address of the server

18.224.52.21

## URL of Application

[http://18.224.52.21/](http://18.224.52.21/)


## Software Installed and Configuration Changes (summary)
Lightspan - Created Lightspan Ubuntu instance per project instructions. Set Lightspan firewall to only allow 2200, 80, 123.

Ubuntu - Ran all updates. Configured sshd.conf file to move ssh to port 2200 and disable password authentication. Set UFW to only allow 2200, 80, 123. Set timezone, etc.

Apache - Installed and configured for http on port 80. 

mod_wsgi - installed and configured via "sites-enabled"

PIP - installed

PYTHON - installed

Flask - installed

PosgreQL - installed and configured for "psql" users

Psycopg2 - installed




## Third Party Resources
Numerous third party resources were used to help complete this project as the Udacity class offers no practical training in executing this task beyond setting up Apache and mod_wsgi for a static output.
I used mutilple online tutorials, examples, YouTube videos, and even hired a tutor for an online session to help explain how to bridge the gap between FLASK and WSGI.


I did not keep an itemized list of every resource I read.


      


