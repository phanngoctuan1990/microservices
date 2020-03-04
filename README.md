# microservices
Microservices with Lumen + Laravel + Nginx + Mysql

## Prerequisites:

- `Docker`
- `Docker-compose`
- `composer`

## Technologies
- `Lumem -v 6.x`
- `Laravel -v 6.x`
- `Nginx`
- `php-7.4`
- `mysql 8.0`

## Setup

`docker-compose build && docker-compose up -d`

### Add host name
`sudo vim /etc/host`

```
127.0.0.1 dispenser.test
127.0.0.1 curator.test
```
