# Use the official Nginx image from Docker Hub
FROM nginx:alpine

# Remove the default nginx website
RUN rm -rf /usr/share/nginx/html/*

# Copy the frontend files from the moviefrontend directory into the Nginx container
COPY ./moviefrontend/ /usr/share/nginx/html/

# Expose port 3000 for Nginx to serve the frontend
EXPOSE 3000
