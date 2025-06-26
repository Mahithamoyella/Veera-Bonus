# Use Node.js base image
FROM node:18

# Set working directory
WORKDIR /app

# Copy files
COPY package*.json ./
RUN npm install

COPY . .

# Expose backend port
EXPOSE 3068

# Run server
CMD ["node", "server.js"]

