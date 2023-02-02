docker build --tag python-docker

docker tag python-docker:latest python-docker:1.0.0

docker rmi python-docker:v1.0.0
