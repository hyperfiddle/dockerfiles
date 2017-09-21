FROM ubuntu:xenial

RUN apt-get update

# Make sure a recent (>6.7.7-10) version of ImageMagick is installed.
RUN apt-get install -y imagemagick

RUN export DEBIAN_FRONTEND=noninteractive && apt-get install -y curl
RUN curl -sL https://deb.nodesource.com/setup_8.x | bash - &&\
  export DEBIAN_FRONTEND=noninteractive &&\
  apt-get install -qq -y nodejs software-properties-common

RUN curl -o- -L https://yarnpkg.com/install.sh | bash -s -- --version 1.0.2
