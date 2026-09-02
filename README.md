# Webs

A lightweight static frontend configured for Alloy development sessions.

## Run with Docker

```sh
docker compose -f docker-compose.alloy.yaml up -d
```

The site is available at `http://localhost:3000`. Alloy proxies the site through
`http://localhost:8080` using `.alloy/environment.json`.
