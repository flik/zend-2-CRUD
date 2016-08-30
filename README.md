# zend-2-CRUD
It is simple CRUD application in Zend 2. Some files were created by Damien G. (damien.galicher@gmail.com). You can email for help.
#Step 1 
Create a database with the name zf2 and import the sql script from folder dbsql.
# Step 2
update files and configure the application with your mysql:
  
config/autoload/global.php

config/autoload/local.php
  
#Step 3 
ZendSkeletonApplication is set up to use Composer (http://getcomposer.org) to resolve its dependencies. In this case, the dependency is Zend Framework 2 itself.

Download the composer.phar 

curl -s https://getcomposer.org/installer | php

# Step 4
just go into application folder and simply type:

php composer.phar self-update

php composer.phar update

#Final Step
just go into application folder and then run the command:

php -S localhost:8090 -t public/

and visit the url: localhost:8090


In case of any issue just clear the cache files from folder: data/cache

Issue will fix other wise check the missing extinsion of php like php_intl.dll
just enable it in php.ini

and then run again
