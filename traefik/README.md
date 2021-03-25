# [Treafik](https://doc.traefik.io/traefik/)
Traefik is a reverse proxy (like [NGINX Reverse Proxy](https://docs.nginx.com/nginx/admin-guide/web-server/reverse-proxy/)) and configures itself almost completely automatically.
It also automatically creates and renews SSL certificates.
The advantage over the NGINX is that the Traefik can be controlled via Docker.

![Image of traefik architecture](https://doc.traefik.io/traefik/assets/img/traefik-architecture.png)

## Setup
1. Copy example env file:
   - ```cp .env.example .env```
2. Configure the .env file:
   - ```vim .env``` or ```nano .env```
3. Create ACME File for lets-encrypt to save certificates:
   - ```touch config/ACME/acme.json```
4. Set Permissions:
   - ```chmod 600 config/ACME/acme.json```
