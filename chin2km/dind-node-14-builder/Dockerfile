FROM docker:latest

RUN apk update && apk upgrade && apk add git openssh bash curl && \
  apk add --update nodejs-current npm && \
  node --version && \
  npm --version && \
  npm i -g yarn
