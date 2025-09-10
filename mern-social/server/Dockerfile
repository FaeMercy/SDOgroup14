FROM node:16-alpine
MAINTAINER group14@griffith.edu.au1
WORKDIR /usr/src/app
COPY ./mern-social/server/package.json .
RUN npm install
COPY ./mern-social/server/ . .
COPY ./mern-social/config/ /usr/src/config/ 
EXPOSE 8800
CMD ["node", "server.js"]
