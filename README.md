# conda-jupyter-base
## prerequisites
- working install of docker
- working version of docker-compose
## how to use
1. cd into repo
2. use `docker compose up -d` to start container
3. use `docker logs conda-jupyter-base-1-conda-1` to get login link for jupyter notebook

## when adding packages to use in notebooks
4. conda packages to add: put commandline innstructions in container/Dockerfile
5. rebuilden with `docker compose up -d --no-deps --build conda`

## extra information
all data is stored in the `./data` dir

