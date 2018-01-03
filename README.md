# Vagrant PHP7 (7.2)

A simple Vagrant LAMP setup running PHP7.2

## What's inside?

- Ubuntu 14.04.3 LTS 
- Vim, Git, Curl, etc.
- Apache
- PHP7.2 with some extensions
- MySQL 5.6
- Node.js with NPM
- RabbitMQ
- Redis
- Composer
- phpMyAdmin

## How to use

- Clone this repository into your project
- Run ``vagrant up``
- Add the following lines to your hosts file (use sudo nano /etc/hosts): 

````
55.55.55.5 app.lan
55.55.55.5 phpmyadmin.lan

````
- Navigate to ``http://app.lan/``
- Navigate to ``http://phpmyadmin.lan/`` (both username and password are 'root')