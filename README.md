Docker Debian Systemd
=====================

This Dockerfile can build containers capable to use systemd.

Branches
--------

This repository has multiple tags that relate to Almalinux versions.

|Debian Version|Docker image tag|
|--------------|----------------------|
| buster (10)   |10, buster           |
| bullseye (11) |11, bullseye, latest |
| bookworm (12} |12, bookworm         |

Manually starting
-----------------

```shell
docker run \
  --tty \
  --privileged \
  --volume /sys/fs/cgroup:/sys/fs/cgroup:ro \
  mullholland/docker-debian-systemd
```
