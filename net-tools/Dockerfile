FROM alpine

LABEL maintainer Jahnin Rajamoni <emailjahnin@gmail.com>

COPY motd /etc/motd

RUN apk add net-tools nano
ENV PS1=" \[\033[1;36m\]\w >\[\033[1;34m\]>\[\033[0m\] "

EXPOSE 22
ENTRYPOINT cat /etc/motd && /bin/sh
