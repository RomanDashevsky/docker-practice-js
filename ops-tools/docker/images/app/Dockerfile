FROM node:12-alpine
WORKDIR /app
RUN npm install -g nodemon
COPY package.json /app
RUN npm install
EXPOSE 8888