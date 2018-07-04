FROM openjdk:8-jre-slim
MAINTAINER "https://github.com/ljufa/docker-images"

ADD kafka-manager-1.3.3.17-dist.tar.gz /opt
RUN cd /opt; \
    mv kafka-manager-1.3.3.17 kafka-manager;

WORKDIR /opt/kafka-manager
ENTRYPOINT ["./bin/kafka-manager"]