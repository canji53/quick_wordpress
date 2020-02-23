# quick_wordpress

## About

Docker Compose to quickly build a Wordpress development environment.
Docker + Nginx + Mysql + PHP = **DUMP...**

## Features

* **Use NGINX** for web server.
* **Use Alpine Image** for weight reduction, <u>but mysql image use debian:stretch-slim.</u>
* **Use phpmyadmin** for development environment.
* Containerized in middleware units.

## Requirement

* Installed Docker

## Usage

```bash
git clone git@github.com:canji53/quick_wordpress.git
cd quick_wordpress
docker-compose up -d
```
