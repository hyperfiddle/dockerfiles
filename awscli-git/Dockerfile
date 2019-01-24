FROM docker:18.06.1-ce-git

RUN apk add --no-cache \
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
