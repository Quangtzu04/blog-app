FROM node:latest
WORKDIR /server
COPY package.json /server
RUN npm install
COPY . /api
CMD node index.js
EXPOSE 5000