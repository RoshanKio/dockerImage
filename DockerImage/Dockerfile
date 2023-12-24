FROM ubuntu:20.04

COPY Hello.java .

WORKDIR /tmp/

ENV NAME "Ram"

COPY Hello.java .

#Running multiple commands
RUN apt-get update && \
	apt-get install -y wget && \
	apt-get install -y openjdk-8-jdk/*

RUN javac Hello.java