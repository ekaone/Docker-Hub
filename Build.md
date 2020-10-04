Build an image from the Dockerfile in the
current directory and tag the image
```
docker build -t myimage:1.0 .
```

List all images that are locally stored with
the Docker Engine
```
docker image ls
```

Delete an image from the local image store
```
docker image rm alpine:3.4
```