# Create a directory where the certificates will be stored
> mkdir certs
> openssl req -x509 -nodes -days 365 -newkey rsa:2048 -keyout certs/localhost.key -out certs/localhost.crt

# Custom domain for development (/etc/hosts)
> 127.0.0.1 api.recipes.io