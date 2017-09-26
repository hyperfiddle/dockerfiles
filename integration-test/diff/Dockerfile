FROM hyperfiddle/imagemagick

RUN export DEBIAN_FRONTEND=noninteractive && apt-get install -y python python-pip curl

RUN curl -sL https://deb.nodesource.com/setup_8.x | bash - &&\
  export DEBIAN_FRONTEND=noninteractive &&\
  apt-get install -qq -y nodejs software-properties-common

RUN curl -o- -L https://yarnpkg.com/install.sh | bash

RUN pip install --upgrade pip awscli s3cmd
RUN mkdir /root/.aws
