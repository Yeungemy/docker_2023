# Specify a base image
FROM node:alpine

# Install some dependencies
# https://stackoverflow.com/questions/57534295/npm-err-tracker-idealtree-already-exists-while-creating-the-docker-image-for
WORKDIR /usr/app
COPY ./ ./
RUN npm install

# Set up a default command
CMD [ "npm","start" ]