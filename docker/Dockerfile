FROM ubuntu:20.04

RUN apt-get update && \
    apt-get upgrade -y && \
    apt-get install -y software-properties-common && \
    add-apt-repository -y ppa:avsm/ppa && \
    apt-get install -y make git gcc ocaml opam pkg-config m4 cmake sudo python2.7 libgmp-dev python3-distutils

RUN curl -s https://packagecloud.io/install/repositories/souffle-lang/souffle/script.deb.sh | bash
RUN apt-get install -y souffle

ENV HOME=/home/student

RUN useradd -ms /bin/bash student

ENV SCRIPT=$HOME/script
RUN mkdir -p $SCRIPT
COPY install-llvm-toolchain.sh $SCRIPT
RUN $SCRIPT/install-llvm-toolchain.sh

RUN sudo adduser student sudo
RUN echo "root:1234" | chpasswd
RUN echo "student:1234" | chpasswd
USER student

COPY install-ocaml.sh $SCRIPT
RUN $SCRIPT/install-ocaml.sh

WORKDIR $HOME
