FROM centos:7
ARG JAVA_VERSION=1.8.0

RUN yum -y update \
    && yum -y install java-${JAVA_VERSION}-openjdk-headless openssl \
    && yum -y clean all
