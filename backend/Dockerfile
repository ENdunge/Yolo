# Fetching node image on apline
FROM node:16-alpine
# Setting up the work directory
WORKDIR /app
COPY package.json package-lock.json ./
COPY . .
EXPOSE 5000
CMD npm start