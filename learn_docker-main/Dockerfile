# Use the official Node.js image
FROM node:21-alpine

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json files to the container
COPY package*.json ./

# Install the dependencies
RUN npm install

# Copy the rest of the application to the container
COPY . .

# Expose the application port
EXPOSE 3000

# Define the command to start the application
CMD ["npm", "start"]
