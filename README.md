# Overview
[![Python application](https://github.com/heyan17/azure-devops-udacity-prj2/actions/workflows/python-app.yml/badge.svg?branch=main)](https://github.com/heyan17/azure-devops-udacity-prj2/actions/workflows/python-app.yml)

This project is an sample of CI/CD using Azure DevOps. This repo will enable you to:
- Deploy an application in Azure Cloud Shell
- Deploy an application as an Azure App Service
- Load testing

## Project Plan

* Trello board for the project: [Trello link](https://trello.com/b/4pBYlosv/azure-cloud-project-2)
* Spreadsheet project plan: [GoogleSheet link](https://docs.google.com/spreadsheets/d/1KYGz4-JPhHJg1KEsSaAOcNnVr4G41t1C/edit?usp=sharing&ouid=104543931335870760692&rtpof=true&sd=true)

## Instructions

* Architectural Diagram

![](./screenshots/01-CDdiagram.png)

* Project running on Azure App Service
abc
![](./screenshots/02-RunningProject.png)

* Project cloned into Azure Cloud Shell
![](./screenshots/02-PrjClonedIntoACS.png)

* Passing tests that are displayed after running the `make all` command from the `Makefile` including output of the test run
![](./screenshots/03-PassingMakeAllTes.png)


** Passing GitHub Action build
![](./screenshots/04-PassingGitActionBuild.png)

* Successful deploy of the project in Azure Pipelines.
![](./screenshots/05-DeployProjectInAzure.png)

* Running Azure App Service from Azure Pipelines automatic deployment
![](./screenshots/06-RunningAzureAppService.png)

* Successful prediction from deployed flask app in Azure Cloud Shell. 
![](./screenshots/07-PredictInACS.png)

* Output of streamed log files from deployed application
![](./screenshots/08-OutputOfStreamedLogFiles.png)

`https://anazdudaprj2.scm.azurewebsites.net/api/logs/docker`
![](./screenshots/09-LogFiles.png)

## Enhancements

- There should be branch for development environment and testing environment separately.
- There should be an mantenance page UI befor production deployment.

## Demo 

Youtube video: https://youtu.be/oBWjMsrTvx0


