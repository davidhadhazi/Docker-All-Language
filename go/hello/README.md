# Docker-Go
This is a go hello world app.

## Running in local enviromnet

Go version
```bash
go version
go version go1.18.1 linux/amd64
```

To run this project (without docker).

```bash
go run .
```

## Building the image and running the container
Only requires docker.

To build the docker image

```bash
docker build . -t go-image:latest
```
To run the docker container

```bash
docker run --name go-container go-image:latest
```
