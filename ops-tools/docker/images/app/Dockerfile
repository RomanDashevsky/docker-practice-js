FROM node:14-alpine

WORKDIR /usr/src/app

COPY package*.json ./

RUN npm install
RUN npm install -g nodemon

COPY app config database public resources start .env server.js ./

EXPOSE 8080
ENTRYPOINT [ "nodemon", "server.js" ]
