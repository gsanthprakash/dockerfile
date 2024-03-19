FROM nginx

# Remove the default index.html file
RUN rm -rf /usr/share/nginx/html/index.html

# Copy your custom index.html file into the nginx HTML directory
COPY q1/ /usr/share/nginx/html/

# Note : files should be available inside the folder in locally.