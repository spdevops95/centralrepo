# Use an official Node.js runtime as a base image
FROM ubuntu

# Set the working directory in the container
WORKDIR /usr/src/app

# Copy package.json and package-lock.json to the working directory
COPY package*.json ./

# Install application dependencies
RUN npm install

# Copy the application code to the container
COPY . .

# Expose a port that the application will run on
EXPOSE 3000

# Define the command to run the application
CMD ["npm", "start"]


