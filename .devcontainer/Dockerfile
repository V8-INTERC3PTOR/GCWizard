# Use the latest Ubuntu LTS as the base image
FROM ubuntu:latest

# Set noninteractive mode to avoid prompts during package installation
ENV DEBIAN_FRONTEND=noninteractive

# Update and install necessary packages
RUN apt-get update && apt-get upgrade -y \
    && apt-get install -y curl git vim sudo unzip xz-utils zip libglu1-mesa \
    && apt-get clean
