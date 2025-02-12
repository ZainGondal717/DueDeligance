# Use Node.js base image
FROM node:18-alpine

# Set the working directory
WORKDIR /app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy all the server code
COPY . .

# Copy the .env file to the container
COPY .env .env

# Expose the port
EXPOSE 3002

# Run the server
CMD ["node", "server.mjs"]
