# base
ARG NODE_VERSION=20-slim
FROM node:${NODE_VERSION}
LABEL maintainer="yaokun <yaokun@bwcxtech.com>"

ENV TZ "Asia/Shanghai"

USER root

RUN npm config set registry https://registry.npmmirror.com \
    && npm install -g cnpm \
    && npm install -g pnpm \
    && pnpm config set registry https://registry.npmmirror.com
