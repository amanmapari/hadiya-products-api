FROM node:16

WORKDIR /app

COPY  package*.json /app

RUN npm install

RUN npm install pm2 -y

COPY . .

EXPOSE 3000

CMD ["npm","start"]
