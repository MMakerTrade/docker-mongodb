[![Build Status](https://travis-ci.org/MMakerTrade/docker-mongodb.svg?branch=master)](https://travis-ci.org/MMakerTrade/docker-mongodb)

# MongoDB

Ready-to-run Docker image with MongoDB.

## Quickstart

```bash
$ docker run --name mongodb -e mmakertrade/mongodb:latest
```

or using Docker Compose:

```yaml
version: '2'

services:
  mongodb:
    image: 'mmakertrade/mongodb:latest'
    ports:
      - '6379:6379'
```

## Building

```bash
$ ./build.sh latest
```