# Introduction

This container provides ElasticSearch and Logstash.

# Building

```
docker build -t tldr/elasticsearch .
```

# Running

```
docker run -d --name elasticsearch -h elasticsearch -p 9200:9200 -p 9300:9300 tldr/elasticsearch
```

# Testing

TODO