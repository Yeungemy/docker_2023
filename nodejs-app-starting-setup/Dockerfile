# base image
FROM node:alpine

# dependencies
WORKDIR /app
COPY package.json /app
RUN npm install
COPY . /app
EXPOSE 80

# default command
CMD [ "npm", "start" ]