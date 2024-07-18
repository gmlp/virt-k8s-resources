# Use the official NGINX base image
FROM nginx:latest

# Copy the static content to the appropriate directory
COPY index.html /usr/share/nginx/html/index.html

# Expose port 80 to the outside world
EXPOSE 80

# Start NGINX when the container launches
CMD ["nginx", "-g", "daemon off;"]
