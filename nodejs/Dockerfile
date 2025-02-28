FROM node:latest

WORKDIR /app

COPY ./esport-api/package*.json ./
RUN npm install

COPY ./esport-api .
EXPOSE 3000

CMD ["npm", "start"]