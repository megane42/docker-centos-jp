# **(((UNOFFICIAL)))** docker-centos-jp

## Build

```
docker build -t megane42/docker-centos-jp \
       --build-arg http_proxy=${http_proxy} \
       --build-arg HTTP_PROXY=${HTTP_PROXY} \
       --build-arg https_proxy=${https_proxy} \
       --build-arg HTTPS_PROXY=${HTTPS_PROXY} \
       .
```

## Run

```
docker run --rm -it megane42/docker-centos-jp bash
```
