from maven:3-jdk-8-slim

RUN apt-get update && \
    apt-get install -y \
      wget \
  && rm -rf /var/lib/apt/lists/*

RUN wget http://ftp.ie.debian.org/debian/pool/main/libp/libpng/libpng12-0_1.2.50-2+deb8u3_amd64.deb -O /tmp/libpng.deb && \
    dpkg -i /tmp/libpng.deb && \
    rm -rf /tmp/libpng.deb
