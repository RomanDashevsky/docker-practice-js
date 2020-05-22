FROM node:12-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install

COPY app config database public resources start .env server.js ./

EXPOSE 8080
ENTRYPOINT [ "npm", "run", "start" ]
