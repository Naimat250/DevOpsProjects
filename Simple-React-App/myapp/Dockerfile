# Use an official Node.js image as a base
FROM node:14-alpine

# Set the working directory
WORKDIR /app

# Copy package.json and package-lock.json (if available)
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy the entire project to the working directory
COPY . .


# Expose the port your app runs on
EXPOSE 3000

# Set the command to run your app
CMD ["npm", "start"]
