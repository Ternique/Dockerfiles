FROM gcc

LABEL maintainer=@joshuacook

RUN apt-get update && \
      apt-get install -y \
      gsl-bin \
      libgsl0-dbg \
      libgsl0-dev \
      libgslcblas0

RUN apt-get install -y gdb 
