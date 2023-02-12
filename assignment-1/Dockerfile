# Use the official Nginx image as the base image
FROM nginx:alpine

WORKDIR /app

# Copy the website files to the default Nginx directory
COPY . .

COPY ./nginx.conf /etc/nginx/nginx.conf