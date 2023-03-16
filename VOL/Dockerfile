FROM node:14-alpine

WORKDIR /app

COPY package.json .
RUN npm install

VOLUME /app/data

COPY . .

CMD ["npm", "start"]