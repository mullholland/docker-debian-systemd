Docker Debian Systemd
=====================

This Dockerfile can build containers capable to use systemd.

Branches
--------

This repository has multiple tags that relate to Almalinux versions.

|Debian Version|Docker image tag|
|--------------|-------------------|
|10            |10                 |
|latest (11)   |11, latest         |
|latest (12}   |12                 |

Manually starting
-----------------

```shell
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  mullholland/docker-debian-systemd
```
