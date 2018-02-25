# HTTP Protocol

To carry out exercises to develop experiential understanding of HTTP protocol, a basic
setup of a *web server* and *web client* is required. It is recommended that these two
should be on different machines (e.g. laptops, desktops etc). For the *web server*, let us
call it *_myweb.com_* and let us consider its IP address to be *10.1.1.1*. This machine
would require a web server, and by default we will assume *Apache* web server
(https://projects.apache.org/project.html?httpd-http_server). 

To install Apache on a linux machine, do the following (ref:
https://www.digitalocean.com/community/tutorials/how-to-install-linux-apache-mysql-php-lamp-stack-on-ubuntu-16-04)

*sudo apt install apache2*

To ensure the web server name works, in the client machine, edit the file */etc/hosts* and
make the following entry.
*10.1.1.1	myweb.com*

To ensure, this web server name is working, open the browser and type the URL
*http://myweb.com* and it should show a Home page of Apache Weh Serber.
