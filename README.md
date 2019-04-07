# docker-compose

![Docker Cloud Build Status](https://img.shields.io/docker/cloud/build/pidelport/docker-cloud.svg)

Docker base image + docker-compose

This uses the official Docker images as base, and adds the official docker-compose binary.

## Related work

### <https://github.com/tmaier/docker-compose>

This build covers more versions of Docker and docker-compose,
but has some concerns, as 2019-04 April:

* Installs using Python 2 pip
* Lacks docker-compose 1.24.0, which adds dependencies that are harder to build
