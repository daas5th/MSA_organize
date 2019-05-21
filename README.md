### Docker Instructions
- To build Dockerfile, run:
`docker build -t organize-service:latest .`

- To run Docker container as a daemon, run:
`docker run -d --net=container:config-service --name organize-service $IMAGE_ID`
