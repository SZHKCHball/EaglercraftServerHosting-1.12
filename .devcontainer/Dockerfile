FROM ubuntu:20.04

RUN apt-get update && apt-get install -y \
    openjdk-17-jdk \
    git \
    curl \
    bash \
    && rm -rf /var/lib/apt/lists/*

WORKDIR /workspace
