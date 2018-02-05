# Create SSL key and certificate
Now that we have a location to place our files, we can create the SSL key and certificate files in one motion by typing:

sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/nginx/ssl/nginx.key -out /etc/nginx/ssl/nginx.crt
