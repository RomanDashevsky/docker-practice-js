FROM node:12-alpine3.11
ADD ./package*.json ./
WORKDIR /app
RUN npm i
EXPOSE 8080
COPY ./docker-entrypoint.sh ./
RUN chmod 0755 docker-entrypoint.sh
ENTRYPOINT [ "docker-entrypoint.sh" ];
