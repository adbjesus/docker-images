FROM debian:buster

ARG USERNAME=compiladores
ARG USER_UID=1000

RUN apt-get update && \
    apt-get install -y llvm-7 clang-7 flex bison && \
    useradd -s /bin/bash -u $USER_UID -m $USERNAME
