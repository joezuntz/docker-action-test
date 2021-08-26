FROM ubuntu:20.04
MAINTAINER joezuntz@googlemail.com

RUN mkdir /opt/placeholder
RUN touch /opt/placeholder/here

ARG GITHUB_SHA
ENV SHA_OF_COMMIT=${GITHUB_SHA}
