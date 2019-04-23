FROM docker/compose:1.24.0

RUN apk update && \
  apk add jq curl py3-pip && \
  ln -s /usr/bin/pip3 /usr/bin/pip

ENTRYPOINT sh
