# https://github.com/AzhakAnwar/python-nogil
This repo contains source code of docker images having Free-Threaded python versions. 


Special thanks to Git repo of the Docker "Official Image" for python at https://github.com/docker-library/python.

You can find the docker images generated from this source code at: https://hub.docker.com/repository/docker/azhak/python3.14-slim-nogil


## Execution:

```
docker build -t "azhak/python3.14-slim-nogil" -f 'Dockerfile.python3.14.3-nogil-slim13.3' .

docker tag azhak/python3.14-slim-nogil:latest azhak/python3.14-slim-nogil:python3.14.3-slim13.3
docker push azhak/python3.14-slim-nogil:latest
docker push azhak/python3.14-slim-nogil:python3.14.3-slim13.3
```
.
