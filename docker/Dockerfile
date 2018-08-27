FROM debian:stretch
LABEL maintainer="Brixcoin Developers <dev@brixcoin.org>"
LABEL description="Dockerised BrixcoinCore, built from Travis"

RUN apt-get update && apt-get -y upgrade && apt-get clean && rm -fr /var/cache/apt/*

COPY bin/* /usr/bin/
