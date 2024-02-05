#Docker-.NET

This is a simple dotnet console app, which counts numbers every second.
This whole project was based on [this site](https://learn.microsoft.com/en-us/dotnet/core/docker/build-container?tabs=linux&pivots=dotnet-8-0)

##Running in local enviromnet

Dotnet version
```bash
dotnet --version
```
```
8.0.101
```

To run this project (without docker)

```bash
dotnet run
```

##Building the image and running the container
Doesn't require any _dotnet_ SDK 

To build the docker image

```bash
docker build . -t ang-image:latest
```

To run the docker container
```bash
docker run --name ang-container ang-image:latest
```

Stop it, by pressing _Ctrl + C_
