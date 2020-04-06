# Overview of Docker Compose
* Compose is a tool for defining and running multi-container Docker applications. With Compose, you use a YAML file to
configure your applications services. Then, with a single command, you create and start all the services from your
configuration.
* Compose works in all evnironment: production, stagin, development, testing as well as CL workflows.
* Using Compose is basically a three-step process:
    * Define your app's environment with a Dockerfile so it can be reproduced anywhere.
    * Define the services that make up your app in docker-compose.yml so they can be run together in an isolated
    environment.
    * Run docker-compose up and Compose starts and runs your entire app.
    
* Can start all services with a single command: docker compose up
* Can stop all services with a single command: docker compose down
* Can scale up selected services when required.

* Limitation of docker-compose
    * docker-compose works only single machine
    
### Reference
* https://sebastianbrosch.blog/docker-stack-nginx-mit-php-7-2-und-mysql/
* http://geekyplatypus.com/dockerise-your-php-application-with-nginx-and-php7-fpm/
* https://www.linode.com/docs/web-servers/nginx/serve-php-php-fpm-and-nginx/
* https://www.ctl.io/developers/blog/post/docker-networking-rules
