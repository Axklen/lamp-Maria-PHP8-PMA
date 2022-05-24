start container

be sure mullvad is not up!!!!!!

```shell
sudo DOCKER_BUILDKIT=0 docker-compose -H unix:///run/podman/podman.sock up -d
```
