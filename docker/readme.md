
Based on: https://github.com/shiguredo/dockerfiles/tree/develop/erlang

sudo docker build -t erlang19.1.2 .
sudo docker run -d -P --name erlang_docker erlang19.1.2
sudo docker inspect id