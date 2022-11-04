FROM node:alpine

WORKDIR /app

EXPOSE 5000

COPY package* ./

RUN npm install

RUN npm fund 

COPY . .

CMD [ "npm", "run", "dev" ]
