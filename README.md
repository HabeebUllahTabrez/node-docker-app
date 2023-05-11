# Node Docker Demo App

This is a basic node.js application created to demonstrate the docker containerization.

1. Command used to build a docker image 
```
docker build -t myapp . 
```

2. Command used to run the container using the previously built image. (Port forwarding included)
```
docker run -p 8080:8080 myapp
```
