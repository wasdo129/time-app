FROM node:alpine

WORKDIR /app

EXPOSE 3000

COPY package*.json ./

RUN npm install

RUN npm fund 

COPY . .

CMD [ "npm", "run", "dev" ]
