### [Radarr](https://github.com/Radarr/Radarr)

```shell
docker run --rm --name radarr -p 7878:7878 -v /tmp/radarr:/config hotio/radarr
```

```yaml
radarr:
  container_name: radarr
  image: hotio/radarr
  ports:
    - "7878:7878"
  volumes:
    - /tmp/radarr:/config
```

```shell
VERSION=image
VERSION=stable
VERSION=unstable
VERSION=https://github.com/Radarr/Radarr/releases/download/v0.2.0.1120/Radarr.develop.0.2.0.1120.linux.tar.gz
VERSION=file:///config/Radarr.develop.0.2.0.1120.linux.tar.gz
```
