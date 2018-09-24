docker run -p 8888:8888 jupyter/scipy-notebook:2c80cf3537ca

docker  exec -it 3b677168b9ec bash

docker cp wine.data 3b677168b9ec:/home/jovyan/work/wine.data

docker run -v /home/user/work/docker-practice/docker_for_DS:/home/jovyan/ -p 8888:8888 jupyter/scipy-notebook:2c80cf3537ca

docker build .

docker run -v /home/user/work/docker-practice/docker_for_DS:/home/jovyan/ -p 8888:8888 96ccfe2745a7

docker build -t my_notebook .

docker run -v /home/user/work/docker-practice/docker_for_DS:/home/jovyan/ -p 8888:8888 my_notebook

docker-compose up

docker-compose stop

docker-compose down

docker-compose up --build

docker volume ls

