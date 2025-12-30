Docker Debian Systemd
=====================

This Dockerfile can build containers capable to use systemd.

Branches
--------

This repository has multiple tags that relate to Almalinux versions.

|Debian Version|Docker image tag|
|---------------|--------------------|
| bookworm (12) | 12, bookworm       |
| trixie   (13) | 13, trixie, latest |

Manually starting
-----------------

```shell
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  mullholland/docker-debian-systemd
```
