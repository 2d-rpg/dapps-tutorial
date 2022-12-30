FROM node:18-alpine

RUN apk update && \
  apk add git zsh

RUN yarn install && yarn add -D \
  hardhat

WORKDIR /home/node/dapps-tutorial

USER node