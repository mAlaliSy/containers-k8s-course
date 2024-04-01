FROM node:20.12.0-alpine

ENV NODE_ENV development

WORKDIR /my-node

COPY . .

RUN npm install

EXPOSE 3000

CMD [ "node", "index.js" ]
