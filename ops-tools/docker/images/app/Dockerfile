FROM node:12-alpine
WORKDIR /home/node/app
COPY ./package*.json /home/node/app/
RUN npm install && mv /home/node/app/node_modules /node_modules

