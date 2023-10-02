# Use an official Node.js runtime as a parent image
FROM node:14

# Set the working directory in the container
WORKDIR /app/products

# Copy package.json and package-lock.json
COPY package*.json .

# Install application dependencies
RUN npm install

# Copy the rest of the application code
COPY . .

# Expose the port that the application will run on
EXPOSE 8002

# Start the application
CMD ["npm", "start"]