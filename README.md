# Vaultwarden Docker-Compose
Vaultwarden Docker-Compose

1. Update `docker-compose.yml`
2. Run `docker-compose up` and make sure nothing errors out. You can use `docker-compose up -d` to start it in the background if you want.
3. Uncomment the approprieate lines in `Caddyfile` to block access to `/admin` after you finish configuring your server.