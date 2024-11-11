FROM nginx:1.27.2

# we copy nginx conf
COPY nginx.conf /etc/nginx/nginx.conf

# copy the certificates
COPY ./server.crt /etc/ssl/certs/server.crt
COPY ./server.key /etc/ssl/private/server.key

# we expose http and https ports
EXPOSE 80 443
