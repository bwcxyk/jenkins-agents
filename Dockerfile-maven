# base
ARG MAVEN_VERSION=3.6.2
FROM maven:${MAVEN_VERSION}-jdk-8-slim
LABEL maintainer="yaokun <yaokun@bwcxtech.com>"

ENV TZ "Asia/Shanghai"

USER root
RUN set -x \
    && apt update \
    && apt install curl wget git -y
