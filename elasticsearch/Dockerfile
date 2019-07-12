#FROM docker.elastic.co/elasticsearch/elasticsearch-platinum:6.2.2
FROM docker.elastic.co/elasticsearch/elasticsearch:7.2.0

LABEL maintainer="zongxj_cn@foxmail.com"

COPY ./config/elasticsearch.yml /usr/share/elasticsearch/conifg/elasticsearch.yml

RUN echo "Asia/Shanghai" > /etc/timezone
