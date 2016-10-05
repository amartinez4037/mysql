# mysql

## Using mysqli vs PDO ##

### [PDO](http://markonphp.com/insert-pdo-prepared-statement/) prepared statements ###

-----

### [MySQLi](http://markonphp.com/simple-select-mysqli-php/) ###
  * Procedural Method
  * OOP Method

## phpMyAdmin ##
 * Set variables to be used on apache restart
  * /etc/dbconfig-common/phpmyadmin.conf
 * Database access settings generated from /etc/dbconfig-common/phpmyadmin.conf file
  * /etc/phpmyadmin/config-db.php
 * Configuration file that overrides settings made by phpMyAdmin setup utility
  * /etc/phpmyadmin/config.inc.php
  
### [SQL Naming Conventions](https://anandarajpandey.com/2015/05/10/mysql-naming-coding-conventions-tips-on-mysql-database/) ###
 * [Check out](http://paul-m-jones.com/archives/6188) Joe Celko's [SQL Programming Style](https://www.amazon.com/Celkos-Programming-Kaufmann-Management-Systems/dp/0120887975/) - [style guide](www.sqlstyle.guide/)
 * [Collation type](http://stackoverflow.com/questions/367711/what-is-the-best-collation-to-use-for-mysql-with-php): utf8_unicode_*
 * General Rules
  * No abbreviations (unless necessary to fit size limits)
  * Use lowercase
  * Underscore to seperate words
  * No numbers
  * Self-explanatory names
  * Less than 64 characters
  * Avoid prefix
  * Be singular
 * Primary keys
  * Keep unique and meaningless - table_name_id or id
 * Foreign key
  * Define foreign key in schema
 * Field Name
  * Do not use reserve words (order, date)
   * Use prefix to make it understandable
  * Avoid using column with same name as table
  * Avoid acronym and abbreviation names
   


