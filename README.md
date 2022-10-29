# container-test
Container console app. Increments and outputs count every second.

# build image
open project in VS Code  
must have [Docker Extension](https://code.visualstudio.com/docs/containers/overview) installed
`ctrl + shift + p`  
use `Docker Images: Build Image...` extension  
use name `containertest:latest` and build image  

# run container
output list of docker images  
`docker image ls`  
you should see image named `containertest` from above 
run command  
`docker run containertest 10`  
it should output 10 events and exit  
