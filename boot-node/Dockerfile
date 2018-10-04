FROM clojure:boot-2.8.1

RUN apt-get -y update

RUN export DEBIAN_FRONTEND=noninteractive && apt-get install -y python python-pip curl

RUN curl -sL https://deb.nodesource.com/setup_10.x | bash - &&\
  export DEBIAN_FRONTEND=noninteractive &&\
  apt-get install -qq -y nodejs software-properties-common
