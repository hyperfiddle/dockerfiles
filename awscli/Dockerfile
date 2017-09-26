FROM docker:17.07.0-ce

RUN apk update && apk add --no-cache \
      bash \
      curl \
      less \
      groff \
      jq \
      python \
      py-pip \
      py2-pip && \
      pip install --upgrade pip awscli s3cmd && \
      mkdir /root/.aws
