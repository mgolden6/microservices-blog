# Select Base Image
FROM node:alpine

# Set Work Directory
WORKDIR /app

# Copy Dependecies
COPY package.json ./

# Install Dependencies
RUN npm install

# Copy Source Code
COPY ./ ./

# Set Default Command
CMD ["npm", "start"]