# Dockerfile for client
FROM node:16.13.0-alpine


WORKDIR /usr/src/app

COPY package.json ./

RUN yarn

COPY . .

EXPOSE 3000

CMD ["npm", "start"]