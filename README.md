# Docker-FROM-Scratch
Starts from the basics - From SCRATCH

This is workbook on the this() lecture

## Some Useful teminology

* Docker is not VM. Its about isolation. Its like full-blown linux kernal running inside almost like a process isolation.
* Image 
  * Your starting point for building something on docker
  * What you produce as an output 
  * It can be compared to Class as in OOPS
* Container
  * A running Image
  * Implementation of a class | Object created from a class as in OOPS
* Host
  * The machine that is running docker | The machine docker in installed on
 
## Docker Commands | PSET 1
``` docker run -it --rm ubuntu /bin/bash ```

-it  - Interactive docker container started. This allows to connect to stdin and we can interact with docker

``` docker ps ``` - lists containers that are running on the machine.

``` docker ps -a ``` - lists all the container that are started and stoped.

``` docker start <container_id> ``` - To restart the container.

``` docker attach <container_id> ``` - To attach the stdio of container to terminal

``` docker stop <container_id> ``` - to stop the running container

``` docker rm <container_id> ``` - to remove container (For cleanup)

## Difference between image and container | PSET 2

TODO
