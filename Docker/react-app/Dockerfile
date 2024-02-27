FROM node:20.11.1-alpine3.19
WORKDIR /app
COPY . .
RUN npm install
ENV API_URL=http://localhost:8080
EXPOSE 3000