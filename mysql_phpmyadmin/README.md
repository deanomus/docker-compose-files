#[MySQL](https://hub.docker.com/_/mysql) & [phpmyadmin](https://hub.docker.com/r/phpmyadmin/phpmyadmin/)
MySQL Server with phpmyadmin as web interface to manage databases.


## What is MySQL? (Copy & Paste from [Docker Hub](https://hub.docker.com/_/mysql))
MySQL is the world's most popular open source database.
With its proven performance, reliability and ease-of-use,
MySQL has become the leading database choice for web-based applications,
covering the entire range from personal projects and websites,
via e-commerce and information services, all the way to high profile
web properties including Facebook, Twitter, YouTube, Yahoo! and many more.


## What is phpmyadmin (Copy & Paste from [Docker Hub](https://hub.docker.com/_/phpmyadmin))
phpMyAdmin is a free software tool written in PHP,
intended to handle the administration of MySQL over the Web.
phpMyAdmin supports a wide range of operations on MySQL and MariaDB.
Frequently used operations (managing databases, tables, columns, relations, indexes,
users, permissions, etc) can be performed via the user interface,
while you still have the ability to directly execute any SQL statement.



##setup
1. Copy example env file:
    - ```cp .env.example .env```
2. Configure the .env file
    - ```vim .env``` or ```nano .env```
3. Create data folder
    - ```mkdir data```