FROM node:12-alpine
WORKDIR /app
RUN npm install -g nodemon
COPY package.json /app
RUN npm install
COPY app config database public resources start server.js ./app/
EXPOSE 8888
CMD [ "nodemon", "server.js" ]