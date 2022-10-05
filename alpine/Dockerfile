FROM alpine:3.16

LABEL \
  org.opencontainers.image.source=https://github.com/holepunchto/prebuild-containers \
  org.opencontainers.image.description="Prebuild container for Alpine Linux" \
  org.opencontainers.image.licenses=ISC

RUN apk --no-cache add \
  g++ \
  gcc \
  git \
  make \
  nodejs \
  npm \
  python3
