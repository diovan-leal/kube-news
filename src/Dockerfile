FROM node:16.5.0
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 8085
CMD ["node", "server.js"]