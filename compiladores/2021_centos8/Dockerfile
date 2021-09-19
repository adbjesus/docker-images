FROM centos:8

ARG USERNAME=compiladores
ARG USER_UID=1000

RUN dnf install -y bash flex bison epel-release && \
    dnf install -y llvm7.0 clang && \
    useradd -s /bin/bash -u $USER_UID -m $USERNAME
