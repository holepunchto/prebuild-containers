FROM ubuntu:18.04

LABEL org.opencontainers.image.source=https://github.com/holepunchto/prebuild-containers
LABEL org.opencontainers.image.description="Prebuild container for Linux"
LABEL org.opencontainers.image.licenses=ISC

RUN \
  apt-get update && \
  apt-get install -y curl software-properties-common

RUN \
  add-apt-repository ppa:git-core/ppa && \
  apt-get update && \
  apt-get install -y git

RUN \
  curl -fsSL https://deb.nodesource.com/setup_16.x | bash - && \
  apt-get install -y nodejs build-essential
