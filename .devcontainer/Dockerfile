FROM mcr.microsoft.com/devcontainers/base:ubuntu
# Install the xz-utils package

#apt-get update && DEBIAN_FRONTEND=noninteractive apt-get install -y --no-install-recommends \
# tzdata \

RUN apt-get update \
    python3 \
    python3-pip \
    scons \
    git \
    cmake \
    stlink-tools \
    curl && \
    rm -rf /var/lib/apt/lists/*
