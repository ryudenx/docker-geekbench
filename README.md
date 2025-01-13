# docker-geekbench

## Run

### Ubuntu base

```
docker build -t ryudenx/geekbench-ubuntu:latest https://github.com/ryudenx/docker-geekbench.git -f Dockerfile_ubuntu
docker run --rm -it --privileged ryudenx/geekbench-ubuntu:latest
```

### Rocky Linux base

```
docker build -t ryudenx/geekbench-rocky:latest https://github.com/ryudenx/docker-geekbench.git -f Dockerfile_rocky
docker run --rm -it --privileged ryudenx/geekbench-rocky:latest
```
