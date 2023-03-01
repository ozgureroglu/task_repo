# jodel Task

This repository contains the code and documentation for;

1. Link to [orchestration diagram](https://drive.google.com/file/d/1EGbxlLv4MdI3h7GhkWxVpDKraHO8J1W7/view?usp=sharing) in Draw.io with explanations on the diagram: 

1. Post service, which was developed as a REST app to mimic the service that was mentioned in the task. That simply includes REST services to create, delete, list messages.
    * A github actions based pipeline has been added to demonstrate the dockerization of the service. 

2. Terraform code to create an EKS cluster on AWS

3. K8S manifests to deploy App, MongoDB Cluster and Redis Cluster

4. Documentation to explain a zero-downtime migration between environments.



## Local Development
1. Project folder contains a docker-compose file to setup local MongoDB and Redis for development. 
2. Run docker-compose up -d before starting to work with the project code itself
3. Project setup
    * Init mongodb databases