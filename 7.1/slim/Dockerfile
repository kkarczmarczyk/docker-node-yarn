FROM node:7.1-slim

MAINTAINER Kamil Karczmarczyk <kkarczmarczyk@gmail.com>

# Global install yarn package manager
RUN npm set progress=false && \
    npm install -g --progress=false yarn

WORKDIR /workspace