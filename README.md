# cakephp_skeleton #
A base for CakePHP application

## How to use ##
```git clone https://github.com/LowG33kDev/cakephp_skeleton my_app_name```

Rename the directory skeleton to your application name (ie: my_app).

Modify the following files: 

 * index.php : define('APP_DIR', 'my_app');
 * .htaccess : 
  * RewriteRule    ^$ my_app/webroot/    [L]
  * RewriteRule    (.*) my_app/webroot/$1 [L]

 After, run ```composer install``` to install CakePHP core files.