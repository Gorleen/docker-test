# Use official Node.js LTS base image
FROM node:16

# Create app directory
WORKDIR /usr/src/app

# Copy package.json files
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy app source code
COPY . .

# Expose port
EXPOSE 3000

# Start app
CMD [ "npm", "start" ]

