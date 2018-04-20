nginx-proxy-upstream is a upstream companion for the [nginx-proxy](https://github.com/jwilder/nginx-proxy).

#### Usage
```bash
$ docker run -d \
    --name nginx-upstream-somename \
    -e VIRTUAL_HOST=foo.bar.com \
    -e UPSTREAM=192.168.12.34:1234 \
    lonwern/nginx-proxy-upstream
```