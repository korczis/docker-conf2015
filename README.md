# README

## Build

```
sudo docker build -t korczis/conf2015 .
```

## Run

```
sudo docker run -p 49160:8080 -d korczis/conf2015
```

## Check status

```
# Get container ID
$ sudo docker ps

# Print app output
$ sudo docker logs <container id>
```

## Curl

```
$ curl -i localhost:49160

HTTP/1.1 200 OK
X-Powered-By: Express
Content-Type: text/html; charset=utf-8
Content-Length: 12
Date: Sun, 02 Jun 2013 03:53:22 GMT
Connection: keep-alive

Hello world
```

