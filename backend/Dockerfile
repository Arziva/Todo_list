# Use a smaller base image
FROM node:12.2.0-alpine

# Set working directory
WORKDIR /usr/app

# Copy only the package files first to leverage Docker cache
COPY package*.json ./

# Install dependencies
RUN npm install --quiet

# Copy the entire project
COPY . .

# Use the recommended syntax for CMD
CMD ["npm", "start"]
