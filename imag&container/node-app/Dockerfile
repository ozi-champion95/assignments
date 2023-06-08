FROM node:14

WORKDIR /nodeapp

COPY package.json /nodeapp

RUN npm install

COPY . /nodeapp

EXPOSE 80 

CMD ["node", "server.js"]