# Mage2-Docker

un-supported Mage2-Docker 

## Services

Nginx 1.14

PHP 7.2

MySQL 5.7

Redis 3.2

## Instructions

### MySQL Set-up


Configure the MySQL Username in : `.env` file

```
MYSQL_ROOT_PASSWORD=root
MYSQL_DATABASE=mage23_db
MYSQL_USER=mage23_web
MYSQL_PASSWORD=mage23pass
```

### Magento document root setup

 - Create a new directory `htdocs`
 - Copy the Magento 2.x source code into the `htdocs` directory.
