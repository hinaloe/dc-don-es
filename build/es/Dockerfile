FROM docker.elastic.co/elasticsearch/elasticsearch-oss:7.0.1

RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch analysis-kuromoji
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch analysis-icu


