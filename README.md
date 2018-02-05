# Create SSL key and certificate
Now that we have a location to place our files, we can create the SSL key and certificate files in one motion by typing:

* sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/nginx/ssl/vc/nginx.key -out /etc/nginx/ssl/vc/nginx.crt
* sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/nginx/ssl/vxm/nginx.key -out /etc/nginx/ssl/vxm/nginx.crt
* sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/nginx/ssl/psc/nginx.key -out /etc/nginx/ssl/psc/nginx.crt
* sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/nginx/ssl/node01/nginx.key -out /etc/nginx/ssl/node01/nginx.crt
* sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/nginx/ssl/node02/nginx.key -out /etc/nginx/ssl/node02/nginx.crt
* sudo openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout /etc/nginx/ssl/node03/nginx.key -out /etc/nginx/ssl/node03/nginx.crt
