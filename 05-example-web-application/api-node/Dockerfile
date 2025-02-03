# the base image of a ubuntu distro
FROM node:19.6-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

USER node

COPY --chown=node:node ./src

CMD ["node", "index,js"]



