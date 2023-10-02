FROM node

WORKDIR /app/customer

COPY package*.json .

COPY .env ./

RUN npm install

COPY . .

EXPOSE 8001

CMD ["npm", "start"]