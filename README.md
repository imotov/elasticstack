# Docker files for starting Elasticsearch and Kibana

## Introduction

This docked compose setup can be used to quickly bring up Elasticsearch and Kibana for local testing.

## Usage

Specify Elasticsearch setup password in `.env` file:
VERSION=7.12.1

Start Elasticsearch and Kibana by running:

```
$ docker-compose up -d
```

After startup you can connect to Elasticsearch at http://localhost:9200/ and Kibana at http://localhost:5601/

When done, stop Elasticsearch and Kibana by running:

```
$ docker-compose down
```

To update the rebuild the image after update run:

```
$ docker-compose build
```
