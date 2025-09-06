FROM node:16-alpine
MAINTAINER group14@griffith.edu.au1
WORKDIR /usr/src/app
COPY package.json ./
RUN npm install
COPY . .
EXPOSE 3000
CMD ["node", "server.js"]
