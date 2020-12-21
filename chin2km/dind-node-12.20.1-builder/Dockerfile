FROM docker:19-dind

RUN apk update && apk upgrade && apk add git openssh bash curl && \
  apk add --update nodejs=12.20.1-r0 npm && \
  node --version && \
  npm --version && \
  npm i -g yarn
