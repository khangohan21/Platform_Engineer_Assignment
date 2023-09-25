FROM node:14
WORKDIR /app
COPY package*.json ./
RUN npm install
COPY . .
EXPOSE 3000
ENV MONGODB_URI=mongodb://13.234.120.211:27017/mydb
ENV REDIS_HOST=13.234.120.211  
ENV REDIS_PORT=6379
CMD ["node", "app.js"]
