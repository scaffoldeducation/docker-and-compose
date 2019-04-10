Adds docker-compose to the [offcial docker image](https://hub.docker.com/_/docker/). 

Using
```
  image: scaffoldeducation/docker-and-compose:18.09.4-1.21.2
  services:****
    - docker:18.09.4-dind
```

Each tag corresponds to a docker image in the format [docker-version]-[docker-compose-version].