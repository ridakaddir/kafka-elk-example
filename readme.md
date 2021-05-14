docker run --network=kafka-elk_default --rm -it -v ${PWD}/pipeline/:/usr/share/logstash/pipeline/ docker.elastic.co/logstash/logstash:7.12.1
