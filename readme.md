# Pi-hole with Cloudflared

## Setup

- Create a file which contains the password for the web-admin-interface: `./pi-hole-webpw.secret`
- You may change the IP address for `HOST_IP` in `.env`, which specifies the source from which DNS requests should be served

## Start

```
docker-compose up -d
```

## Releases

- [docker-pi-hole](https://github.com/pi-hole/docker-pi-hole/releases)
- [cloudflared](https://github.com/cloudflare/cloudflared/releases/tag/2025.7.0)
