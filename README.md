# AndroidCICD

Project created to run a CI/CD for Native Android.

## Description

This project was created to run CI/CD pipeline for Native Android using GitHub Actions (CI) and Firebase App Distribution (CD) or
Jenkins (local CI) and App Center (CD).
* TODO: Add Jenkins to Azure
* TODO: Trigger Jenkins build when pushing a commit to GitHub repo main branch.

## Getting Started

### Dependencies

* local Jenkins (for now)

### Installing

* Install the latest LTS version: brew install jenkins-lts
* Update the Jenkins version: brew upgrade jenkins-lts

### Executing program

* Start the Jenkins service: brew services start jenkins-lts
* Restart the Jenkins service: brew services restart jenkins-lts
* Open Jenkins at: http://localhost:8080/
  
## Authors

Ricardo Numa
koki_numa@hotmail.com

## Version History

* 0.1
    * Initial Release
