FROM node:16-alpine
WORKDIR /app
COPY package.json yarn.lock ./
COPY . .
EXPOSE 5000
CMD npm start