FROM node:16.13.0 

WORKDIR /app

COPY package*.json ./

RUN npm install -qy
RUN npm start

COPY . .

CMD ["npm", "run", "dev"]

EXPOSE 3000