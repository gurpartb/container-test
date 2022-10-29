# container-test
Open project in VS code

# build image
`ctrl + shift + p`
Use `Docker Images: Build Image...` extension
use name `containertest:latest` and build image

# run container
output list of docker images
`docker image ls`
you should see image named `containertest` from above
`docker run containertest 10`
command above should run container using image above and exit after 10 events