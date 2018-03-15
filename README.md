# Docker with PHP, NodeJS and Yarn

![Docker Automated build status](https://img.shields.io/docker/build/roelofr/php-node.svg)
![Docker Automated build](https://img.shields.io/docker/automated/roelofr/php-node.svg)

This project is a Docker container based on `roelofr/php` with the installed scripts from the Node Library image (`node`), which installs NodeJS and Yarn.

The Dockerfile fetches the latest releases for Yarn and NodeJS from GitHub and installs those, after doing a signature check.

Due to the installation process, you'll receive the `curl`, `zip`, `gnupg` and `jq` binaries.

## How to use

To use it, install it from [Docker Hub](https://hub.docker.com/r/roelofr/php-node/), or use the command below.

```sh
docker pull roelofr/php-node
```

