### My Docker Kibana Setup

Just a simple docker setup with elastic + kibana linked for development. 

## Install 
Just clone the repo and execute this from cli: 
```
docker-compose -d up 
```

## Verify that elastic works:
```
curl -v http://localhost:9200/		
```

## Verify that kibana works:
```
curl http://0.0.0.0:5601 --location
```

## Visit in your browser:
http://0.0.0.0:5601/ kibana on port 5601
http://0.0.0.0:9200 /elastic on port 9200/9300

## Images and version:
docker.elastic.co/elasticsearch/elasticsearch:7.5.0
docker.elastic.co/kibana/kibana:7.5.0


