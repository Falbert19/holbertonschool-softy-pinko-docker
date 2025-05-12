This directory is for Task 2 of the Docker exercise,
which involves creating a Docker image that runs a simple Flask API

can be run by:

docker build -f Dockerfile -t softy-pinko:task2 .
docker run -p 5252:5252 softy-pinko:task2