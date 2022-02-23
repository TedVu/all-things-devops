FROM node:17-alpine3.14


RUN mkdir /usr/local/nodejs-bindmount


WORKDIR /usr/local/nodejs-bindmount

COPY . .

RUN npm install

EXPOSE 3000

CMD ["npm", "run", "develop"]