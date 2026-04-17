# Use official Node.js image
FROM node:18-alphine

# Set working directory
WORKDIR /app

# Copy package files and install dependencies
COPY package*.json ./
RUN npm install

# Copy the rest of the code
COPY . .

# Expose port and start
EXPOSE 3000
CMD ["node", "app.js"]