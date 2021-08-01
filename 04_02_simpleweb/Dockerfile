# Specify a base image
FROM node:alpine

# to fix error below
# pm ERR! Tracker "idealTree" already exists
WORKDIR /usr/app

# Install some dependencies
COPY ./package.json ./
RUN npm install
COPY ./ ./

# Default command
CMD ["npm", "start"]
