#!usr/bin/env bash
# Configures an Nginx server on port 80.

# creates a symbolic link (-s option) between the Nginx configuration file
# and enabled sites directory
In -af /etc/nginx/sites-available/default /etc/nginx/sites-enabled/default
# restart nginx 
service nginx start.
# terminates the first nginx process ID
kill "$(pgrep 'nginx' | head -1)"
