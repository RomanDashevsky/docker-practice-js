FROM node:12-alpine3.11
EXPOSE 8080

WORKDIR /app
ADD ./package*.json ./
WORKDIR /app
RUN npm i

COPY ./ops-tools/docker/images/app/docker-entrypoint.sh /docker-entrypoint.sh
ENTRYPOINT ["sh", "/docker-entrypoint.sh" ]
