FROM node:20

WORKDIR /app

COPY . .

RUN npm install

WORKDIR /app/services/gateway
RUN npm install
RUN npm run build

CMD ["npm", "start"]
