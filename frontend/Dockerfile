FROM node

# Create app directory
RUN mkdir -p /frontend
WORKDIR /frontend

COPY package*.json ./
RUN npm install
RUN chown -R node:node /frontend/node_modules