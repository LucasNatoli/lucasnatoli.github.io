# High Performance Wordpress Installation

## Componentes

+ Balanceador de carga
+ Webserver/s
+ Servidor de Base de datos
+ Memcached
+ NFS

## Master droplet 

Install

+ Nginx (ws)
+ php fpm + modules
+ Certbot
+ NFS host

Config

+ nginx conf domain.tld
+ nginx conf cache
+ certificados
+ fs exports /etc/exports

## Mysql Droplet

Install

+ mysql

config

+ secure installation
+ listen on private network
+ create db and class C network users

## Memcached Droplet

(pending)


## Provision droplets

Install 
+ NFS commons
+ Nginx

Config

+ mount en /etc/fstab
+ nginx conf copiada
+ certificados copiados
