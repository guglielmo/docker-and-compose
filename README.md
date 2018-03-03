Adds docker-compose to the [offcial docker image](https://hub.docker.com/_/docker/). 
Originally taken from jonaskello/docker-and-compose:1.12.1-1.8.0,
and modified in order to advance docker and docker-compose versions.

Can be used for docker-in-docker in GitLab like this:

```
  image: guglielmo/docker-and-compose:latest
  services:
    - docker:18-dind
```

Each branch in this repo corresponds to a docker image in the format [docker-version]-[docker-compose-version].
