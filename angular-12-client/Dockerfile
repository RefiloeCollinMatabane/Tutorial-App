FROM node:12-alpine

WORKDIR /src/app

COPY package*.json ./

COPY . .

RUN npm install

CMD [ "node", "server.js" ]