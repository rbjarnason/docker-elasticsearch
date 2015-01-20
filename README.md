docker-elasticsearch
====================

docker run -d --restart="always" -e ES_HEAP_SIZE=8g -v /media/es_data:/data -p 9200:9200 -p 9300:9300 yrpri/elasticsearch
