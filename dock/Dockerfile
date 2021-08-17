FROM ubuntu:20.04
MAINTAINER joezuntz@googlemail.com
#Joe's note to himself.  Compile this with: docker build -t joezuntz/cosmosis-base .
#then docker push joezuntz/cosmosis-base

# Basic compilers and tools dependencies
RUN apt-get update -y && DEBIAN_FRONTEND="noninteractive" apt-get install -y gcc g++ gfortran \
    cmake swig wget make libopenblas-dev libchealpix-dev \
    pkg-config curl python3 python3-distutils python3-dev python3-pip \
    libcfitsio-dev  libfftw3-dev   git  libgsl-dev autoconf \
    && apt-get clean all

