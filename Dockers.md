# Dockers
***
#### Dockers Installation


![dockers](https://user-images.githubusercontent.com/34166599/109562250-247bf880-7aac-11eb-8b8e-9c5935aa9f6f.JPG)

![dockers2](https://user-images.githubusercontent.com/34166599/109562284-2e9df700-7aac-11eb-8788-985104ec14b2.JPG)

![dockers3](https://user-images.githubusercontent.com/34166599/109562317-38275f00-7aac-11eb-9a7d-509f7d11aadf.JPG)

![dockers4](https://user-images.githubusercontent.com/34166599/109562373-4b3a2f00-7aac-11eb-8fd8-e114dd727a5c.JPG)

![dockers5](https://user-images.githubusercontent.com/34166599/109562403-5725f100-7aac-11eb-85c3-bae9d144b4dc.JPG)

![dockers6](https://user-images.githubusercontent.com/34166599/109562625-a0764080-7aac-11eb-9b84-33e29bfdf334.JPG)


## Docker vs Host Machine

* Host operating system is the operating system on which the Docker client run. The Host Operating system shares its kernel with running Docker containers.
* Docker runs processes in isolated containers. A container is a process which runs on a host. When an operator executes docker run , the container process that runs is isolated in that it has its own file system, its own networking, and its own isolated process tree separate from the host.
* A docker container image just has a kind of filesystem snapshot of the linux-image the container image is dependent on. The container-image includes some basic programs like bash-shell, vim-editor etc to facilitate developer to work easily with the docker image. 
* Docker behind the scene uses the host OS which is linux itself to run its containers. The programs included in linux-like filesystem snapshot that we see in form of docker containers actually runs on the host OS in isolation.
