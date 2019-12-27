# Micro Service - Zipkin Server
# Author GeekTech
# Version 1.0.0

FROM geekcarnegie/centos:1.0
MAINTAINER GeekTech
VOLUME /tmp
ADD zipkin-server-1.0.0.jar zipkin-server.jar
RUN bash -c 'touch /zipkin-server.jar'
ENTRYPOINT ["java", "-Djava.security.egd=file:/dev/./urandom", "-jar", "/zipkin-server.jar"]