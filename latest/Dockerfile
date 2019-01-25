FROM docker:latest

RUN apk update && \
  apk add py3-pip && \
  apk add curl && \
  ln -s /usr/bin/pip3 /usr/bin/pip && \
  pip install docker-compose
