FROM ubuntu:22.04

RUN apt-get update
RUN apt-get install -y wget make

RUN wget https://golang.google.cn/dl/go1.17.7.linux-amd64.tar.gz
RUN tar -C /usr/local -zxf go1.17.7.linux-amd64.tar.gz
ENV PATH=$PATH:/usr/local/go/bin

