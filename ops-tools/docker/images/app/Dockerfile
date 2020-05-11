FROM node:14-alpine3.11
ADD ./ ./
WORKDIR /app
RUN npm i
EXPOSE 8080
CMD [ "npm", "run", "start:dev"];
