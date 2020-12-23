
docker pull goafabric/elasticsearch-arm64v8:5.4.3-SNAPSHOT && docker run --rm -p9200:9200 -p9300:9300 goafabric/elasticsearch-arm64v8:5.4.3-SNAPSHOT
docker run --rm -it --entrypoint /bin/bash goafabric/elasticsearch-arm64v8:5.4.3-SNAPSHOT


