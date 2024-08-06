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
