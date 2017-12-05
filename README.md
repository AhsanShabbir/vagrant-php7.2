# Vagrant PHP7 

A simple Vagrant LAMP setup running PHP7.

## What's inside?

- Ubuntu 14.04.3 LTS 
- Vim, Git, Curl, etc.
- Apache
- PHP7 with some extensions
- MySQL 5.6
- Node.js with NPM
- RabbitMQ
- Redis
- Composer
- phpMyAdmin

## How to use

- Clone this repository into your project
- Run ``vagrant up``
- Add the following lines to your hosts file:
````
55.55.55.5 ahsanshabbir.dev
55,55.55.5 phpmyadmin.dev
````
- Navigate to ``http://ahsanshabbir.dev/`` 
- Navigate to ``http://phpmyadmin.dev/`` (both username and password are 'root')