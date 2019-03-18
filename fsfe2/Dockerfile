FROM node:11-alpine

RUN mkdir -p /home/fsfe2
WORKDIR /home/fsfe2
# VOLUME /home/fsfe2

RUN yarn global add forever

COPY . .

RUN yarn install

CMD forever ./app.js
