FROM node:16.13.0 

WORKDIR /app

COPY package*.json ./

RUN npm install -qy

COPY . .

CMD ["npm","run", "start"]

EXPOSE 3000