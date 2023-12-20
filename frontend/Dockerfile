# Use a smaller base image
FROM node:12.2.0-alpine

# Set working directory
WORKDIR /app

# Copy just the package.json and package-lock.json first to leverage Docker cache
COPY package*.json ./

# Install dependencies
RUN npm install --quiet

# Copy the entire project
COPY . .

# Expose the port if your application requires it
# EXPOSE 8080

# Start the app
CMD ["npm", "run", "serve"]
