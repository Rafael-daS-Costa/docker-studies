FROM node

WORKDIR /app

COPY package.json /app

RUN npm install

COPY . /app

ENV PORT 80

# Porta de dentro do container
EXPOSE $PORT

# ["dentro do container"]
# VOLUME ["/app/feedback"]

CMD ["npm", "start"]