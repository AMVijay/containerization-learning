# Docker

## DockerFile Syntax and Reserved Words
* FROM
    * First keyword in Docker File. 
    * it defines which type of base image needed for the new docker image creation. 
    * Example:  
`FROM alpine:latest`  
`FROM ubuntu:latest`
* RUN
    * Used to execute any commands while building the docker image.
    * Example: 
    ```
    FROM ubuntu:latest
    RUN apt update
    ```
* CMD
    * Used to execute commands while docker is running.
* EXPOSE
* ENV
    * To set Environment variable.
* ADD
    * To add files from URL to Docker Images.
* COPY
    * To copy files from local to Docker images.
* WORKDIR 
    * To set working directory in docker image. After this command, any command will be executed from this working directory.