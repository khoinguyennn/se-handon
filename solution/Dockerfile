# Use an Nginx image to serve the frontend
FROM nginx:alpine

# Copy the built frontend files to the Nginx HTML directory
COPY . /usr/share/nginx/html

# Expose the frontend port
EXPOSE 80

# Start Nginx
CMD ["nginx", "-g", "daemon off;"]