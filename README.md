To find the version of docker
```
docker version
```

To find more details on docker
```
docker info
```

To download and install nginx docker image from docker hub
```
docker container run --publish 80:80 nginx
```

To run nginx docker image in the background
```
docker container run --publish 80:80 --detach nginx
```
It returns the container id.

To list all containers
```
docker container ls
```

To stop a container
```
docker container stop <first few chars of container id>
```

Remove a container
```
docker container rm <container id> <container id> ...
```
