# nginx + PHP FPM Docker container

Alpine based container to build Magento1+2 containers on top of it. It uses Supervisord (http://supervisord.org/) to start nginx, PHP FPM, Postfix and a cron daemon.



## Build image


docker build -t  <username>/<image-name> .


docker push <username>/<image-name>:master
