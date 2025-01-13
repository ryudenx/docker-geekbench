FROM ubuntu:18.04

LABEL maintainer="Ryuden <master+geekbench@ryuden.org>"

# install
RUN apt-get update \
    && apt-get install wget -y \
    && wget https://cdn.geekbench.com/Geekbench-6.3.0-Linux.tar.gz \
    && tar xf Geekbench-6.3.0-Linux.tar.gz

WORKDIR /Geekbench-6.3.0-Linux/
ENTRYPOINT [ "/Geekbench-6.3.0-Linux/geekbench_x86_64" ]