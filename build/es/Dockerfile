FROM docker.elastic.co/elasticsearch/elasticsearch:7.17.1

RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch analysis-kuromoji
RUN /usr/share/elasticsearch/bin/elasticsearch-plugin install --batch analysis-icu


