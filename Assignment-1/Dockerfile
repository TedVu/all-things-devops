FROM node:17-alpine3.14


COPY server.js server.js

COPY package.json package.json

RUN npm install

EXPOSE 3000

CMD ["npm" ,"start"]