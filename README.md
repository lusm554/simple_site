## Simple site, simple server.

### You can run it from Docker Hub
```Docker
docker run -dp 80:8080 "loveyousomuch/simple_site"
```
and then go to `http://localhost:80`

## OR

### Build docker image
```Docker
docker build -t simple_site .
```

### Run docker container
```Docker
docker run -dp 80:8080 loveyousomuch/simple_site
```
