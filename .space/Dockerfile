FROM ubuntu:20.04
ENV DEBIAN_FRONTEND=noninteractive ENV LC_ALL=C.UTF-8
RUN apt-get update && apt-get install -y apt-utils apt- transport-https
RUN apt-get install -y \
# Utilities \
curl unzip wget software- properties-common socat man-db gnupg2 pass lsof \
# VCS \
git \
# Docker
docker docker-compose \
# Required tools
cowsay
RUN apt update
RUN apt install postgresql postgresql-contrib -f -y
