FROM node:18.20.4-alpine

WORKDIR /app

COPY package*.json /app

RUN npm install

COPY . .

EXPOSE 5173

CMD ["npm", "run", "dev", "--", "--host", "0.0.0.0"]
