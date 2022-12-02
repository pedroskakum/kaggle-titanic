# Kaggle Titanic

## Instalation and enviroment default
https://towardsdatascience.com/how-to-run-jupyter-notebook-on-docker-7c9748ed209f#09a3

cmd:
`docker run -p 8888:8888 -v %cd%:/home/jovyan/work jupyter/scipy-notebook`

powershell:
`docker run -p 8888:8888 -v ${PWD}:/home/jovyan/work jupyter/scipy-notebook`

linux:
`docker run -p 8888:8888 -v $(pwd):/home/jovyan/work jupyter/scipy-notebook`

-----

`docker container ls`
`docker exec -it <CONTAINER_ID> /bin/bash`

### Choosing another images
[jupyter-docker-stacks.readthedocs.io](https://jupyter-docker-stacks.readthedocs.io/en/latest/using/selecting.html)


additional links:

[jupyter.org/install](https://jupyter.org/install)

[pipenv.pypa.io](https://pipenv.pypa.io/en/latest/)
