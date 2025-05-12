This directory is for Task 3, which connects
the front-end to the Flask API backend

Can be run by:

terminal #1
docker build -f ./back-end/Dockerfile -t softy-pinko-back-end:task3 ./back-end
docker run -p 5252:5252 softy-pinko-back-end:task3

in terminal #2

docker build -f ./front-end/Dockerfile -t softy-pinko-front-end:task3 ./front-end
docker run -p 9000:9000 softy-pinko-front-end:task3

then open:

http://localhost:9000