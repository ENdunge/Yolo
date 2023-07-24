# Fetching the latest node image on apline linux
FROM node:alpine AS builder

# Declaring env
ENV NODE_ENV production

# Setting up the work directory
WORKDIR /app

# Installing dependencies
COPY ./package.json ./
RUN npm install

# Copying all the files in project
COPY . ./


# Building our application
RUN npm run build

# Fetching the latest nginx image
EXPOSE 3000

CMD ["start"]