# CI/CD Pipeline 

## Service 
we are using circleci for our CI/CD pipeline.

## Configuration
you can find the configuration in the .circleci/config.yml file.

## Steps of the pipeline

* install node (version 16.13)
* setup aws cli and eb cli
* install frontend dependencies
* build frontend
* deploy frontend
* install backend dependencies
* build backend
* deploy backend
