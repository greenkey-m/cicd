FROM node:10-alpine

RUN mkdir /usr/vueapp
WORKDIR /usr/vueapp
COPY package.json yarn.lock ./
RUN yarn
ENTRYPOINT yarn prod