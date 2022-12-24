FROM node:14-alpine as base

WORKDIR /usr/app

COPY package*.json ./

RUN npm ci -qy

COPY . .

EXPOSE 3000

CMD ["npm", "start"]