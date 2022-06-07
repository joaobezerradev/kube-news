FROM node:16.14.2
WORKDIR /app
COPY package*.json ./
RUN npm i
COPY . .
EXPOSE 8080
CMD [ "node","server.js" ]