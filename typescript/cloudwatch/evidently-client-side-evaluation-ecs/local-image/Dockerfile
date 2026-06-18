FROM node:23.11.1-alpine3.21

WORKDIR /app

COPY . /app

RUN npm install && npm install typescript -g && tsc

EXPOSE 80

CMD ["node", "app.js"]
