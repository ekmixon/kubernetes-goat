FROM node:16.8.0-alpine3.13
LABEL MAINTAINER="Madhu Akula" INFO="Kubernetes Goat"

WORKDIR /usr/src/app

COPY code/package*.json ./

RUN npm install \
    && apk add --no-cache curl

COPY code/* ./

EXPOSE 3000

CMD [ "npm", "start" ]
