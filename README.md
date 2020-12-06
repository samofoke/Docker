# Docker
hands on Devops
An introduction to Docker
### The installation process of docker.
* Well the is an easy way to insatll docker by going to this link https://docs.docker.com/install/linux/docker-ce/ubuntu/ the is way to install docker using a script:
~~~
$ curl -fsSL https://get.docker.com -o get-docker.sh
$ sudo sh get-docker.sh
~~~
* After is done you can run sudo docker version to check the version of docker you using. Also go to docker hub to find a container to use test if you docker runs without any errors.
* we run docker run to start a container
~~~
docker run nginx
docker ps -> it displays all running processes
docker ps -a
docker stop [name of the container] -> this command stops a container that's running.
docker rm [name of the container] -> this command removes the the container.
~~~
* When you want to see a list of images
~~~
docker images -> it list all the images you pulled.
docker rmi [name of the image] -> this command removes the image.
~~~
* whem you want just to pull the image but not run it.
~~~
docker pull [name of the image]
~~~