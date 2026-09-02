# webs

A minimal static frontend configured for Alloy development sessions.

## Run locally

```sh
docker compose -f docker-compose.alloy.yaml up -d
```

The frontend listens on <http://localhost:3000>. Alloy proxies it through
<http://localhost:8080> during a session.
