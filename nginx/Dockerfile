# Specify nginx image to build from
FROM nginx

# Remove existing nginx.conf
RUN rm /etc/nginx/nginx.conf

# Copy new nginx.conf to server
COPY ./nginx.conf /etc/nginx