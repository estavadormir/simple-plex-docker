# simple-plex-docker

I was in need of a Simple Plex server using docker compose, so I've come up with this config:

Radarr, Sonarr, Prowlarr, qbittorrent, overseerr, flaresolverr, watchtower, autoheal

Give proper permissions to your media folders depending on the group id and user id, for instance if you use 1000:

```
sudo chown 1000:1000 ./path
```
