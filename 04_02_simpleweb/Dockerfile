# Specify a base image
FROM node:alpine

# to fix error below
# pm ERR! Tracker "idealTree" already exists
WORKDIR /usr/app

# Install some dependencies
COPY ./ ./
RUN npm install

# Default command
CMD ["npm", "start"]
