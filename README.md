# jenkins-pipeline-examples

This repository provides sample Jenkinsfile to create pipelines in Jenkins CI tool

It is assumed the user has some familiarity with Jenkins and UI. To use the sample Jenkinsfile you will have to create a pipeline project and modify some parameters as per instructions given in respective Jenkinsfile

### 1. Jenkinsfile-git-java-maven
This file has 3 stages:
1. Checkout code - Check out the code from git repository
2. Build - Build and package the checked out code using maven
3. Archive Results - Archive results using **Archive Artifacts** plug in
