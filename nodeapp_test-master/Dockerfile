FROM node:latest

WORKDIR nodeapp_test-master/Dockerfile

COPY package.json ./

RUN npm install

COPY . .

EXPOSE 4000
CMD [ "node", "index.js" ]
