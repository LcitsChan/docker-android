FROM ubuntu:16.04

MAINTAINER lcitschan <ctairong@gmail.com>

RUN DEBIAN_FRONTEND=noninteractive && \
	apt-get --quiet update -y && \
	apt-get --quiet install -y openjdk-8-jdk && \
    apt-get clean && \
    rm -rf /var/lib/apt/lists/*

ENV JAVA_HOME /usr/lib/jvm/java-8-openjdk-amd64