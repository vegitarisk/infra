# Use the official Nginx image as the base image
FROM nginx:latest

# Copy custom nginx configuration file
COPY nginx.conf /etc/nginx/nginx.conf

# Create the html folder where web content will be served from
RUN mkdir /usr/share/nginx/html

# Copy your web content into the html folder
COPY html /usr/share/nginx/html
