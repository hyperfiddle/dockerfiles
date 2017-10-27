FROM clojure:boot-2.7.2

RUN apt-get -y update

RUN export DEBIAN_FRONTEND=noninteractive && apt-get install -y python python-pip curl

RUN curl -sL https://deb.nodesource.com/setup_8.x | bash - &&\
  export DEBIAN_FRONTEND=noninteractive &&\
  apt-get install -qq -y nodejs software-properties-common
