# docker
Belajar Docker Code
#
```
docker container create --name myredis redis:latest
```
#
````
docker container start myredis
````
#
````
docker container create --name myredis -p 6379:6379 redis:latest
````
#
````
docker run --name my-container -d -p 8080:80 nginx
````
#
````
docker volume create my-data
````
#
````
docker run -d -p 8080:80 --name my-app-volume -v my-data:/usr/share/nginx/html nginx:alpine
````
#
````
docker next
````
