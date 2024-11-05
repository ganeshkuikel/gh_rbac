FROM node:20-alpine

WORKDIR /frontend

# Copy package.json and package-lock.json to the container
COPY package*.json ./

# Install dependencies
# RUN npm install --legacy-peer-deps

COPY . .

# RUN npm install --legacy-peer-deps

# RUN npm install
EXPOSE 3009

# Start the application
# CMD ["sh", "-c", "npm run dev"]