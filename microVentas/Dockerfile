FROM node:latest

EXPOSE 3003

WORKDIR /microVentas

COPY src/controllers /microVentas/controllers
COPY src/models /microVentas/models
COPY src/index.js /microVentas

RUN npm init --yes
RUN npm install express morgan mysql mysql2 axios

CMD node index.js
