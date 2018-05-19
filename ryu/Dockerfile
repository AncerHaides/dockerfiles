FROM ubuntu:18.04

RUN apt-get update \
&& apt-get install -y --no-install-recommends \
curl iproute2 vim ryu-bin python3-redis \
&& ln -s /usr/bin/python3 /usr/bin/python \
&& rm -rf /var/lib/apt/lists/*
