# play2.2-docker
Docker integration for a Play Framework 2.2.6 application

The build script uses play stage to prepare the application for production deployment.
The dockerfile exposes play default http port 9000

## A couple of assumptions 
SSL Offloading is assumed, so no configuration is present at this layer.
No activator support.
Docker is installed and a local repository is present
The build script generates the docker image in the local repository
