FROM node:16.13.0 

WORKDIR /usr/app

COPY package*.json ./
COPY ./yarn.lock ./


RUN yarn install

RUN npm install -qyg nodemon@2.0.7
RUN npm install -qy

COPY . .

CMD ["nodemon", "-L", "index.js"]

EXPOSE 8000