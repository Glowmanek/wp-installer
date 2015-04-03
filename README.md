# wp-installer
***Automates Wordpress installation on Debian/like systems***

###This script makes the following actions:

#####Install
* apache2
* php5
* php5-gd
* php5-mysql
* libapache2-mod-php5 
* mysql-server

#####Download the lastest WordPress tar ball
https://wordpress.org/latest.tar.gz
#####Configure MySQL database for Wordpress
* Create Database
* Create User
* Set privileges

Change the values on the script **[line 5 and 6]**
#####Configure server root
Change valeu if you want other directory **[Default: /var/www (line 3)]**

###Usage
    $ git clone https://github.com/fnk0c/wp-installer.git
    $ cd wp-installer
    $ ./wp-installer.sh
