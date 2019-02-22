# Docker Stack for Apache2.4 and php7.2 environment

## Summary

A simple Dockerfile for apache 2.4 and php-fpm 7.2

- Based on debian
- With apache 2.4 + php-fpm7.2
- Custom apache 2.4, php7.2 and supervisord configurations
- No database

## Usage

## Development

Download: 

```
git clone git@github.com:foss-cafe/docker-apache-fpm.git apache-php-fpm && cd apache-php-fpm 
```

Build:

```
docker build -t apache-php-fpm .;
docker run \
-p 8o:80 ;
```
Open browser http://localhost:80/info.php

### Debugging

Login:

```
docker exec -it apache-php-fpm /bin/bash
```
