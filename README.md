# traefik-le (traefik v1)

Configuration for Traefik as proxy with SSL using Let's Encrypt.

## Install & Run

### HTTP challenge

```
git clone git@github.com:ondrejsika/traefik-le.git
cd traefik-le
docker-compose up -d
```

### DNS challenge (cloudflare)

Run also in private networks or on localhost

```
git clone git@github.com:ondrejsika/traefik-le.git
cd traefik-le
cp .env.template .env
vim .env  # Update your CloudFlare credetials
docker-compose -f compose.cloudflare.yml up -d
```
