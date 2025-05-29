# Alternate and more conventional way to interact (enter) with Docker Containers

```
$ docker exec -it {container id} bash
```

## Steps:

1. Pull a docker image
```
$ docker pull ubuntu-latest
```

2. Open the docker container in Detached mode
```
$ docker run -itd ubuntu-latest
```

3. Check the docker container ID
```
$ docker ps
```

4. Attach to the docker container
```
$ docker exec -it {image id first 3} bash
```

![img](img/Docker_exec.png)
