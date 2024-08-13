FROM node:22-alpine3.19
WORKDIR /app
COPY package*.json ./
COPY . /app
RUN npm install 
CMD [ "npm","run","dev","--","--host=0.0.0.0","--port=3000"]