# Simple Symfony2 deployment with docker and nginx load balancer

Requirements
 
 Install Docker: https://docs.docker.com/engine/installation
 Install Docker-compose: https://docs.docker.com/compose/install
 
clone this project 

Replace the Symfony2 app path in docker-compose.yml

`/symfony/app/path:/var/www/api`

####### Run the following commands
```
docker-composer up  OR sudo docker-composer up 

```
GO to the url and Test
http://localhost
