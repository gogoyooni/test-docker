FROM node:20-alpine


WORKDIR /server
COPY . .

RUN npm install

CMD "nodemon -L index.js"