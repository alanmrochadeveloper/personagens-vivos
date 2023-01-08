FROM node:18-alpine

WORKDIR /home/app/api

COPY ./ ./

RUN yarn install

COPY ./package.json ./

ENTRYPOINT [ "yarn start:dev" ]