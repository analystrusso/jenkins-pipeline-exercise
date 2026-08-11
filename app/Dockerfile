FROM alpine:3.14

EXPOSE 3000

WORKDIR /home/app

COPY package*.json .

RUN apk add libatomic \
    && npm install

COPY . .

CMD ["node", "server.js"]


