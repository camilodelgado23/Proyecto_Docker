FROM node:latest

EXPOSE 3002

WORKDIR /microProductos

COPY src/controllers /microProductos/controllers
COPY src/models /microProductos/models
COPY src/index.js /microProductos/

RUN npm init --yes
RUN npm install express morgan mysql mysql2 axios xlsx

CMD node index.js
