## lightgbm-gpu
lightgbm gpu version

## docker pull command
docker pull gammagao/lightgbm-gpu  

## Quickstart

### Run Image

```sh
nvidia-docker run --rm -d --name gammagao/lightgbm-gpu -p 8888:8888 -v /home:/home gammagao/lightgbm-gpu
```

### Attach with Command Line Access (if required)

```sh
docker exec -it gammagao/lightgbm-gpu bash
```

### Jupyter Notebook

```sh
localhost:8888
```
