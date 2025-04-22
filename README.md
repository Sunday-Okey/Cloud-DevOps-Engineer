# Project: Deploy a high-availability web app using CloudFormation

In this project, I deployed web servers for a highly available web app using CloudFormation. I wrote the code that creates and deploys the infrastructure and application for an Instagram-like app from the ground up. I began by deploying the networking components, followed by servers, security roles, and software following best practices, automation and scripting as much as possible.

## Project Scenario

A company is creating an Instagram clone called Udagram, and the requirement is to deploy this new application to the AWS infrastructure using Infrastructure as Code (IaC).
We are tasked with provisioning the required infrastructure and deploying a dummy application, along with the necessary supporting software. Since the underlying network infrastructure will be maintained by a separate team, we must create independent stacks for the network infrastructure and the application itself. Infrastructure spin up and tear down needs to be automated so that each team can create and discard testing environments on demand.

![image](https://github.com/user-attachments/assets/1892c251-7db8-4efc-b8bf-2b1b6cdcb149)


## Project Diagram


![image](https://github.com/user-attachments/assets/b3f1e4b2-5516-4ac8-a13d-0a18cacbd8bf)



