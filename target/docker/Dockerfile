FROM dockerfile/java
MAINTAINER Nepomuk Seiler
ADD files /
WORKDIR /opt/docker
RUN ["chown", "-R", "daemon", "."]
USER daemon
ENTRYPOINT ["bin/akka-docker-cluster"]
CMD []
