FROM node:12-alpine3.11
ADD ./package*.json ./
WORKDIR /app
RUN npm i
EXPOSE 8080
ENTRYPOINT [ "npm", "run" ];
CMD [ "migration:run", "start:dev"];
