
This repository contains configuration files for building a 
Docker (http://docker.io) image for Tiny Tiny RSS web-based news feed (RSS/Atom) reader/aggregator.

## Noteworthy

* TinyTiny-rss (https://tt-rss.org/)

## Build your own image

```shell
$ docker build -t <your-name>/ttrss .
```

## Get a pre-built image

A current image is available as a trusted build from the Docker index:

```shell
$ docker pull  cyrilix/ttrss
```

The repository page is at
https://index.docker.io/u/cyrilix/ttrss/


## Run a container with this image

```shell
$ docker run \
  --detach \
  --publish 8080:8080 \
  <your-name>/ttrss

```

## Configuration

Create posgresql database.
