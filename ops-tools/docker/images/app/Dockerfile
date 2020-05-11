FROM node:14-alpine3.11

ADD ./ ./

RUN node --version && npm --version && netstat -ntulp
EXPOSE 5432
EXPOSE 6379
WORKDIR /app

CMD [ "npm", "run", "start"];
CMD netstat -ntulp
CMD [ "npm", "run", "start"];
