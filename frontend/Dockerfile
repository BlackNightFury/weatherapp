FROM node:10.16.0

WORKDIR /usr/app

COPY package*.json ./

RUN npm install -qy

COPY . .

EXPOSE 8000

CMD ["npm", "start"]
