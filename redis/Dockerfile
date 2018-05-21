FROM redis:latest

RUN apt-get update \
&& apt-get install -y --no-install-recommends vim iputils-ping \
net-tools iproute2 lsof curl \
&& rm -rf /var/lib/apt/lists/*
