# Fetching node image on apline
FROM node:16-alpine
# Setting up the work directory
WORKDIR /app
# Installing dependencies
COPY package.json package-lock.json ./
RUN npm install
COPY . .
EXPOSE 5000
CMD npm start