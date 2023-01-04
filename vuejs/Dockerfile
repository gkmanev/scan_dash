# syntax=docker/dockerfile:1.4
FROM node:14.4.0-alpine 
RUN mkdir /project
WORKDIR /project

COPY . .

RUN yarn global add @vue/cli
RUN yarn install
CMD ["yarn", "run", "serve"]


