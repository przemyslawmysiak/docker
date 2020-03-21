# docker
Docker Compose YML file with:

* MySQL 5.7
* phpmyadmin
* wordpress
* mailhog

# mysql config:

* username: wordpress
* password: wordpress
* root password: wordpress
* database name: wordpress

# phpmyadmin config:

* url: http://dev.localhost:8080 or http://localhost:8080

# wordpress config

* domain: http://dev.localhost
* hostname: dev
* to change: volumes path and working_dir
* to change: domainname and hostname

# mailhog config:

* url: http://dev.localhost:8025 or http://localhost:8025
* to use with WordPress, please install plugin: https://github.com/Kubitomakita/mailhog-wp-smtp
