FROM nginx:1.23.3-alpine

# Copy your custom nginx.conf (if you have one)
# Uncomment the line below if you're using a custom nginx.conf file
# COPY ./nginx.conf /etc/nginx/nginx.conf

# Copy the default.conf file (where your server block is configured)
COPY ./default.conf /etc/nginx/conf.d/default.conf

# Expose port 80 (default HTTP port)
EXPOSE 80
