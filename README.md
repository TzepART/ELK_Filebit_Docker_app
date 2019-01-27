# ELK&Filebit Docker
This example on base this [ELK-Docker project](https://github.com/sqshq/ELK-docker) with connecting Filebit
There are using:
* [ElasticSearch](https://www.elastic.co/products/elasticsearch) to store and index log data.
* [Logstash](https://www.elastic.co/products/logstash) to preprocess log files.
* [Kibana](https://www.elastic.co/products/kibana) as web-interface.
* [Filebeat](https://www.elastic.co/products/beats/filebeat) to collect and send log files to Logstash

## Setup
1. Install Docker and Docker Compose on the ELK host
2. Clone this repository and hit `docker-compose build`

## Usage
Start everything with one command:
```
docker-compose up
```