FROM nginx

# Remove the default index.html file
RUN rm -rf /usr/share/nginx/html/index.html

# Copy your custom index.html file into the nginx HTML directory
COPY index.html /usr/share/nginx/html/index.html
