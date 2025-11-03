# Use a lightweight Nginx image as the base for serving static content
FROM nginx:alpine

# The Nginx base image runs the web server on port 80 by default.
EXPOSE 80

# Remove the default Nginx index.html file
RUN rm -rf /usr/share/nginx/html/*

# Copy your local index.html file into the Nginx web root directory inside the container
COPY index.html /usr/share/nginx/html/index.html

# The default command (CMD) for the nginx:alpine image is sufficient to start the server.
# The server will automatically start and serve your index.html file on port 80.
