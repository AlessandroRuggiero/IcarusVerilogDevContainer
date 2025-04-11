# Use the base image from the devcontainer.json file
FROM mcr.microsoft.com/devcontainers/base:jammy

RUN apt-get update && \
    apt-get install -y --no-install-recommends && \
    apt-get install iverilog -y && \
    apt-get install gtkwave -y