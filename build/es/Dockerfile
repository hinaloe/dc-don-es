FROM docker.elastic.co/elasticsearch/elasticsearch-oss:6.8.9

RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch analysis-kuromoji
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch analysis-icu


