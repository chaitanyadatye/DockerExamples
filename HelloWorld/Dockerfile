FROM ubuntu:16.04

RUN apt-get update && apt-get -y upgrade && apt-get -y install gawk bc

ADD helloworld.sh /usr/local/bin

CMD ["/bin/bash"]
