# Set nginx base image
FROM nginx

# File Author / Maintainer
MAINTAINER Citrix Config Service

# Copy custom configuration file from the current directory
COPY default.conf /etc/nginx/conf.d/default.conf

COPY html /usr/share/nginx/html
