FROM node:10.16.0

WORKDIR /usr/app

COPY package*.json ./
RUN npm install -qy

COPY . .

EXPOSE 9000

CMD ["npm", "run", "dev"]
