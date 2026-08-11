FROM node:20-bullseye

EXPOSE 3000

COPY app/ /home/app

WORKDIR /home/app

RUN npm install

CMD ["node", "server.js"]


