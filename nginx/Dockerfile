# Use the official Nginx image as a base
FROM nginx:alpine

RUN rm /etc/nginx/conf.d/default.conf
# Copy Nginx configuration file
COPY ./nginx.conf /etc/nginx/conf.d/default.conf

# Expose port 80 (the default port for Nginx)
EXPOSE 80

# Command to run Nginx
CMD ["nginx", "-g", "daemon off;"]
