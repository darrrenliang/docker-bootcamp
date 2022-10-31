#### Build docker image
`docker build -t webserver .`

### Run docker image
- The -it switch allows me to stop the container using Ctrl-C from the command-line
- The –rm switch ensures that the container is deleted once it has stopped
`docker run --rm -it -p 8082:80 webserver`

### Remove docker image
`docker image rm webserver --force`