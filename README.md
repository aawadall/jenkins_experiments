# Jenkins Experiment
In this repository, I am experimenting with Jenkins.

## Plan
1. Instantiate a Jenkins server on GCP from the Jenkins GCP Marketplace image.
2. Create two Node JS applications;
    1. One will be API Server
    2. The other will be Angular Client
3. Each application will have its own Dockerfile
4. Each application will have its own Jenkinsfile
5. I will configure GitHub Webhooks to trigger Jenkins builds
6. I will configure Jenkins to push Docker images to Docker Hub

## Journal 
* Feb 4, 2023:
    * I have created a Jenkins Server on GCP using Bitnami's Jenkins image.