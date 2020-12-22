FROM node:14.15.1-alpine3.10

WORKDIR /app

COPY ./package.json ./

RUN npm install --silent
ENV PATH /app/node_modules/.bin:$PATH

EXPOSE 3000

CMD [ "npm", "start" ]