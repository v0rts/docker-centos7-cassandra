# CentOS 7 Cassandra 

[![Docker Automated build](https://img.shields.io/docker/automated/v0rts/docker-centos7-cassandra?maxAge=2592000)](https://hub.docker.com/r/v0rts/docker-centos7-cassandra/)

CentOS 7 Docker image +Cassandra for testing

## How to Build

This container is built with any commit to the `master` branch of this repo. If you wish to build the image locally, do the following:

  1. [Install Docker](https://docs.docker.com/engine/installation/).
  2. `cd` into this directory.
  3. Run `docker build -t centos7-cassandra .`

## How to Use

  1. [Install Docker](https://docs.docker.com/engine/installation/).
  2. Pull this image from Docker Hub: `docker pull v0rts/docker-centos7-cassandra:latest` (or use the tag you built earlier, e.g. `centos7-cassandra`).
  3. Run a container from the image: `docker run -t -d v0rts/docker-centos7-cassandra`
  3. Attach to container: `docker exec -t -i container_id /bin/bash`

## Notes


## Author

Created by v0rts (v0rts@getitsolutions.net)
