# Docker ML Environment
Docker description of Machine/Reinforcement learning development environment, including:
* Pytorch
* Tensorflow
* Tensorflow Probabilities
* Tensorflow Agent
* Conda
* Jupyterlab
* CUDA/Cudnn

### Build the image
```bash
docker build .
```

### Run Image
You need to be using a machine with the proper NVIDIA drivers installed.

### Some docker commands
On this section we will show some usefull docker commands.

#### List all local docker images
```bash
docker images
```

#### Build docker image from Dockerfile
```bash
docker build -t ${IMAGE_NAME}:${VERSION} .
```

#### List all running containers
```bash
docker ps
```

#### Remove a container
```bash
docker rm ${CONTAINER_ID}
```

#### Remove an image
```bash
docker rmi ${IMAGE_ID}
```


