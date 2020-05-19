FROM node:12-alpine
RUN apk add --no-cache bash
WORKDIR /app
COPY package.json /app
RUN npm install
EXPOSE 8888