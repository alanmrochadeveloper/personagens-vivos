FROM node:18-alpine

WORKDIR /home/app/client

COPY ./ ./

RUN yarn install

COPY ./package.json ./

ENTRYPOINT [ "yarn dev" ]