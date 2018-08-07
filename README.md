# Traefik SSL Proxy

    Ondrej Sika <ondrej@ondrejsika.com>
    https://github.com/ondrejsika/traefik-ssl

Configuration for Traefik as proxy with SSL.


## Install & Run

```
git clone git@github.com:ondrejsika/traefik-ssl.git
cd traefik-ssl
openssl req -newkey rsa:2048 -nodes -keyout certs/key.pem -x509 -days 365 -out certs/cert.pem
docker-compose up -d
```
