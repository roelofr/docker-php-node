# Docker with PHP, NodeJS and Yarn

![Docker Automated build status][1]
![Docker Automated build][2]
![Travis build status][3]

<!-- badges -->
[1]: https://img.shields.io/docker/build/roelofr/php-node.svg?label=Docker+Build
[2]: https://img.shields.io/docker/automated/roelofr/php-node.svg
[3]: https://img.shields.io/travis/github/roelofr/docker-php-node.svg?label=Travis+build

This project is a Docker container based on `roelofr/php` with the installed scripts from the Node Library image (`node`), which installs NodeJS and Yarn.

The Dockerfile fetches the latest releases for Yarn and NodeJS from GitHub and installs those, after doing a signature check.

Due to the installation process, you'll receive the `curl`, `zip`, `gnupg` and `jq` binaries.

## How to use

To use it, install it from [Docker Hub](https://hub.docker.com/r/roelofr/php-node/), or use the command below.

```sh
docker pull roelofr/php-node
```

