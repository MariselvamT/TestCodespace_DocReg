#
# Ubuntu Dockerfile
#
# https://github.com/dockerfile/ubuntu
#
    
# Pull base image.
FROM ubuntu:latest

RUN wget -q https://packages.microsoft.com/config/ubuntu/16.04/packages-microsoft-prod.deb

Run apt-get install eclipse-temurin -y

# [Optional] Uncomment this section to install additional OS packages.
# RUN apt-get update && export DEBIAN_FRONTEND=noninteractive \
#     && apt-get -y install --no-install-recommends <your-package-list-here>
