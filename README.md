# README

Run `sudo docker run -d -p 127.0.0.1:9200:9200 -p 127.0.0.1:9300:9300 -e "discovery.type=single-node" docker.elastic.co/elasticsearch/elasticsearch:7.17.8` to setup docker container

Run `sudo docker stop ${name}` to shut it down
