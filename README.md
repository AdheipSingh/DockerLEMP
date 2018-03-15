# DockerLEMP
DEPLOYMENT OF LEMP STACK ON DOCKER CONTAINERS
In order to solve the issue of php-fpm consuming a lot of swap in the traditional LEMP STACK deployment , i found a much better way of deploying LEMP STACK using CONTAINERS .
A simple docker-compose file can link all the services nginx , mariadb , php-fpm and php-myadmin ( if you want phpmyadmin ) all four on different containers , each running seperatly and all linked together in a small cluster . 
