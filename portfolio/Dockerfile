# Use the official Nginx image as the base image
FROM nginx:alpine

# Copy your static files into the Nginx web directory
COPY . /usr/share/nginx/html

# Expose port 80 to allow external access
EXPOSE 80

# Start Nginx when the container launches
CMD ["nginx", "-g", "daemon off;"]