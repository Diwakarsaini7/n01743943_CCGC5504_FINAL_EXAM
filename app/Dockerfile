# Use official NGINX image as base
FROM nginx:alpine

# Copy custom index.html to NGINX document root
COPY index.html /usr/share/nginx/html/

# Expose port 80
EXPOSE 80

# Start NGINX in foreground
CMD ["nginx", "-g", "daemon off;"]