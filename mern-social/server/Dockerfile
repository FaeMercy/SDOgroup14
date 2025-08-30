FROM node:16-alpine
MAINTAINER group14@griffith.edu.au1
WORKDIR /usr/src/app
RUN npm install
COPY . .
EXPOSE 5000
CMD ["node", "server.js"]
