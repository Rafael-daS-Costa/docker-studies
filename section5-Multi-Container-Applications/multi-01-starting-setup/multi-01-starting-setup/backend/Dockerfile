FROM node:18-alpine

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . .

EXPOSE 80

ENV MONGODB_USERNAME=root
ENV MONGODB_PASSWORD=secret

CMD ["npm", "run", "dev"]