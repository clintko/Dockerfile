FROM ubuntu:18.04
#FROM nvidia/cuda:10.1-cudnn7-devel-ubuntu16.04 FAILED
#FROM nvidia/cuda:10.1-cudnn7-devel-ubuntu18.04 FAILED
#FROM nvidia/cuda:10.0-cudnn7-devel-ubuntu16.04 SUCCEED

LABEL maintainer="clintko"
USER root

RUN apt-get update && apt-get -y install curl && apt-get -y install build-essential
RUN apt-get -y install cowsay
RUN echo 'alias cowsay="/usr/games/cowsay"' >> ~/.bashrc
