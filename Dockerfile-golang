# base
ARG GOLANG_VERSION=1.17
FROM golang:${GOLANG_VERSION}
LABEL maintainer="yaokun <yaokun@bwcxtech.com>"

ENV TZ "Asia/Shanghai"

USER root
RUN set -x \
    && apt update \
    && apt install curl wget git -y
