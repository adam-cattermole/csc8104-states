from node:latest

WORKDIR /usr/src/states

COPY package.json .

RUN npm install

COPY server.js db.json ./

EXPOSE 8080

CMD [ "node", "server.js" ]
