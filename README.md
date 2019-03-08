# node-calibre-docker

[![](https://images.microbadger.com/badges/version/msimmer/node-calibre.svg)](https://microbadger.com/images/msimmer/node-calibre "Version")
[![](https://images.microbadger.com/badges/image/msimmer/node-calibre.svg)](https://microbadger.com/images/msimmer/node-calibre "Image Layers")
[![](https://images.microbadger.com/badges/commit/msimmer/node-calibre.svg)](https://microbadger.com/images/msimmer/node-calibre "Commit")
[![](https://images.microbadger.com/badges/license/msimmer/node-calibre.svg)](https://microbadger.com/images/msimmer/node-calibre "License")

A NodeJS v9 Docker image with calibre

## Build

```
$ docker build . -t msimmer/node-calibre -f ./Dockerfile
```

## Run

```
$ docker run -dit msimmer/node-calibre
```

## Test

```
$ docker exec -it <name> /bin/bash
```

## Publish

```
$ ./version.sh # <major|minor|patch>
$ ./publish.sh
```
