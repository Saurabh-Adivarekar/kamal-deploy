# Use the official Nginx base image
FROM nginx:latest

# Copy custom Nginx configuration file
COPY custom-nginx.conf /etc/nginx/conf.d/default.conf

# Copy static website files to the default web root directory
COPY ./static-html /usr/share/nginx/html

# Expose the default Nginx port
EXPOSE 80