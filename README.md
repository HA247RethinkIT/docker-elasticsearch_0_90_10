## ElasticSearch 0.90.10, Dockerfile



### Base Docker Image

* [dockerfile/ubuntu:trusty](http://dockerfile.github.io/#/ubuntu)


### Installation

1. Install [Docker](https://www.docker.com/).

2. Download from public [Docker Hub Registry](https://registry.hub.docker.com/): `docker pull ha247/elasticsearch_0_90_10`

   (alternatively, you can build an image from Dockerfile: `docker build -t="ha247/elasticsearch_0_90_10" github.com/HA247RethinkIT/docker-elasticsearch_0_90_10`)


### Usage

#### Run

    docker run -d --name mysql -p 9200:9200 ha247/elasticsearch_0_90_10

