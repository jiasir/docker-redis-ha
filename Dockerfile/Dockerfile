FROM ubuntu:14.04

MAINTAINER jiasir <jiasir@icloud.com>

RUN apt-get update && apt-get install redis-server redis-tools -y
ADD conf/redis.conf.master /etc/redis/redis.conf
CMD ['redis-server']