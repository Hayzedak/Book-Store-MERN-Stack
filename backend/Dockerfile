FROM node:20.15.0-alpine

WORKDIR /app

COPY package*.json .

RUN npm install

COPY . .

EXPOSE 5555

CMD [ "npm", "start" ]
