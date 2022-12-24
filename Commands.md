## Check if Docker is installed Successfully

```
$ docker run hello-world
```

This will auto download an docker image from the internet and generate a message in terminal showing "Docker has been installed successfully"

## Check Total Images

```
$ docker images
```

## Process Status

https://docs.docker.com/engine/reference/commandline/ps/

```
$ docker ps
```

## Process Status [Show all containers]

```
$ docker ps --all/-a
```

Here it shows all the created as well as the destroyed ones

## Detatch

Statrt Container in the detatched mode and give it a name

```
$ docker run --name CONTAINER_NAME -d IMAGE_NAME/ID
```

returns an ID

## Interactive Mode

Helps in keep running the image

```
$ docker run --name CONTAINER_NAME -it -d IMAGE_NAME/ID
```

## Run Specific Command in your Container

example: I want to run python3 inside my container

```
docker exec -it CONTAINER_ID python3
```

## Docker Inspect (All Container Information)

```
docker inspect CONTAINER_ID
```
