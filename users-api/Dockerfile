FROM node:14-alpine@sha256:4e84c956cd276af9ed14a8b2939a734364c2b0042485e90e1b97175e73dfd548

WORKDIR /app

COPY package.json .

RUN npm install

COPY . .

EXPOSE 3000

CMD [ "node", "users-app.js" ]