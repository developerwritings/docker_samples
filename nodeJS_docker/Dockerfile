FROM node:16

WORKDIR /usr/src/project_name

COPY package*.json ./

RUN npm install

COPY . .

EXPOSE 8080

CMD [ "node", "index.js" ]