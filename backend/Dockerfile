FROM node:18-alpine AS build

WORKDIR /app

COPY package*.json ./

RUN npm install express mysql2 cors nodemon

COPY . .

EXPOSE 5000

CMD ["npm"]