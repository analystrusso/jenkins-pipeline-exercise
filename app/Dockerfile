FROM node:26-alpine

EXPOSE 3000

WORKDIR /home/app

COPY package*.json .

RUN npm install

COPY . .

CMD ["node", "server.js"]


