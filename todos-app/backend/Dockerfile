FROM node:alpine

WORKDIR /app

COPY package.json .

RUN npm install

# Install Bash
RUN apk add --no-cache bash

COPY . .

EXPOSE 8000

CMD ["npm", "run", "start"]
