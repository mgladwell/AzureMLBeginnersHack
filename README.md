# AzureMLBeginnersHack

| Lab # | Activity |
| ------------- | ------------- |
| 1  | [Set up](Lab_1.md)|
| 2  | AutoML  |
| 3  | Notebook  |

## Overview
In this lab, we will learn how to set up an environment to start developing Machine Learning (ML) solutions on Azure Machine Learning (Azure ML) service with native modules, R and Python scripts. Microsoft Azure ML is a cloud service that provides ready-to-use templates and APIs as a solution to various problems such as fraud, anomaly detection, sentiment analysis, face recognition, etc. Along with these APIs, it is also possible to develop custom solutions with custom algorithms even by integrating custom R or Python scripts.

Azure ML is a subscription-based online service that can be accessed through a regular web browser. It offers [guest, free, and standard tier services](https://learn.microsoft.com/en-us/azure/machine-learning/overview-what-is-azure-machine-learning?view=azureml-api-2). With some limitations, guest access doesn't require any login process. Without an account and with just a few clicks, you can start developing ML solutions. Other tiers require a Microsoft account, and we will develop most of our experiments, R and Python scripts in the free or standard tier environment. The main difference between the free and the standard account is performance. The free account has resource limitations, resulting in lower performance and execution speed in experiments. To have a general knowledge of other platforms, we will also set up R and Python app development environments.

## Objectives
This set of labs will show you how to:

1. Set up a free Microsoft Azure ML workspace
  1a. Set up an Azure ML workspace within an existing Azure subscription
2. Set up an AutoML Experience
  2a. What is AutoML?
  2b. Create a Data Asset
  2c. Create a compute cluster to host the AutoML job
