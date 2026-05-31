[![GitHub stars](https://img.shields.io/github/stars/tazihad/byedpi-docker.svg)](https://github.com/tazihad/byedpi-docker/stargazers)
[![GitHub license](https://img.shields.io/github/license/tazihad/byedpi-docker.svg)](https://github.com/tazihad/byedpi-docker/blob/main/LICENSE)
![GitHub build Status](https://img.shields.io/github/actions/workflow/status/tazihad/byedpi-docker/build.yml)
![Docker Stars](https://img.shields.io/docker/stars/tazihad/byedpi.svg)
![Docker Pulls](https://img.shields.io/docker/pulls/tazihad/byedpi.svg)
![Docker Image Version](https://img.shields.io/docker/v/tazihad/byedpi?label=version)

Usage: 

**Docker**
```
docker run --rm -p 127.0.0.1:1080:1080 --name byedpi tazihad/byedpi --disorder 1 --fake 0 --ttl 1 --auto=torst --tlsrec 1+s --debug 1
```

**Podman**
```
podman run --rm -p 127.0.0.1:1080:1080 --name byedpi tazihad/byedpi --disorder 1 --fake 0 --ttl 1 --auto=torst --tlsrec 1+s --debug 1
```

Adjust config.

**Use socks5**  
```
socks5://127.0.0.1:1080
```



[ByeDPI project](https://github.com/hufrea/byedpi)
