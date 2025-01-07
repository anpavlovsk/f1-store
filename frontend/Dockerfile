# Use Nginx as the base image
FROM nginx:latest

# Copy static files to the Nginx HTML directory
COPY index.html /usr/share/nginx/html/index.html

# Expose the Nginx port
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]
