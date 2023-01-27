FROM node:18.11.0
workdir /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8080
CMD [ "node",  "server.js"] 
