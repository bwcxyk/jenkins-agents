# base
ARG NODE_VERSION=16-slim
FROM node:${NODE_VERSION}
LABEL maintainer="yaokun <yaokun@bwcxtech.com>"

ENV TZ "Asia/Shanghai"

USER root

RUN npm config set registry https://registry.npmmirror.com \
    && npm install -g cnpm@9.2.0 \
    && npm install -g pnpm@6.35.1 \
    && pnpm config set registry https://registry.npmmirror.com
