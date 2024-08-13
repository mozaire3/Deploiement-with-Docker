FROM node:22-alpine3.19
WORKDIR /app
COPY package*.json ./
COPY . /app
RUN npm install
CMD [ "npm","run","start" ]