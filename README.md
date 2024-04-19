# Overview
[![Python application](https://github.com/heyan17/azure-devops-udacity-prj2/actions/workflows/python-app.yml/badge.svg?branch=main)](https://github.com/heyan17/azure-devops-udacity-prj2/actions/workflows/python-app.yml)

This project is an sample of CI/CD using Azure DevOps. This repo will enable you to:
- Deploy an application in Azure Cloud Shell
- Deploy an application as an Azure App Service
- Load testing

## Project Plan

* Trello board for the project: [Trello link](https://trello.com/invite/b/4pBYlosv/ATTI0f0017ffb2e91391630a7026edfac431750C5A2A/azure-cloud-project-2)
* Spreadsheet project plan: [GoogleSheet link](https://docs.google.com/spreadsheets/d/1KYGz4-JPhHJg1KEsSaAOcNnVr4G41t1C/edit?usp=sharing&ouid=104543931335870760692&rtpof=true&sd=true)

## Instructions

* Architectural Diagram
![](./screenshots/01-CDdiagram.png)

* Project running on Azure App Service


* Project cloned into Azure Cloud Shell
![](./screenshots/02-PrjClonedIntoACS.png)

* Passing tests that are displayed after running the `make all` command from the `Makefile` including output of the test run
![](./screenshots/03-PassingMakeAllTes.png)


** Passing GitHub Action build
![](./screenshots/04-PassingGitActionBuild.png)

* Successful deploy of the project in Azure Pipelines.  [Note the official documentation should be referred to and double checked as you setup CI/CD](https://docs.microsoft.com/en-us/azure/devops/pipelines/ecosystems/python-webapp?view=azure-devops).

* Running Azure App Service from Azure Pipelines automatic deployment

* Successful prediction from deployed flask app in Azure Cloud Shell.  [Use this file as a template for the deployed prediction](https://github.com/udacity/nd082-Azure-Cloud-DevOps-Starter-Code/blob/master/C2-AgileDevelopmentwithAzure/project/starter_files/flask-sklearn/make_predict_azure_app.sh).
The output should look similar to this:

```bash
udacity@Azure:~$ ./make_predict_azure_app.sh
Port: 443
{"prediction":[20.35373177134412]}
```

* Output of streamed log files from deployed application

> 

## Enhancements

<TODO: A short description of how to improve the project in the future>

## Demo 

<TODO: Add link Screencast on YouTube>


