FROM node:latest

EXPOSE 3001

WORKDIR /microUsuarios

COPY src/controllers /microUsuarios/controllers
COPY src/models /microUsuarios/models
COPY src/index.js /microUsuarios/

RUN npm init --yes
RUN npm install express morgan mysql mysql2 axios

CMD node index.js
