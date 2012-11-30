# Drupal 7 Installation Profile for Agofer.com.co #

Install Profile for a Drupal7 version of Agofer.com.co

## Requirements ##

* A machine with **Apache**, **MySQL**, **git** and **drush** has been set up.
* A MySQL database has been created for Drupal, and a user has been given full access to it.

## Installation ##

Copy the file **build-agofer.make** to your home dir

Run
 
  drush make build-agofer.make /var/www/agofer
  cd /var/www/agofer
  drush site-install agofer --db-url=mysql://<database_user>:<database-user-password>@<database host>/<database name>

