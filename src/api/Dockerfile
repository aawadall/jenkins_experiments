# Dockerfile for Express JS API
FROM node:18.10.0-alpine3.13

# Create app directory
WORKDIR /usr/src/app

# Copy package.json and package-lock.json
COPY package*.json ./

# Install dependencies
RUN npm install

# Copy source code
COPY . .

# Expose port 3000
EXPOSE 3000

# Run the app
CMD [ "npm", "start" ]