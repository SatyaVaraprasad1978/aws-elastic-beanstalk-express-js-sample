# Overview
- In this tutorial, you will create a continuous delivery pipeline for a simple web application. You will first use a version control system to store your source code. Then you will learn how to create a continuous delivery pipeline that will automatically deploy your web application whenever your source code is updated.
# What You Will Learn
- This tutorial will walk you through the steps to create the continuous delivery pipeline discussed above. You will learn to:
    - Set up a GitHub repository for the application code
    - Create an AWS Elastic Beanstalk environment to deploy the application
    - Configure AWS CodeBuild to build the source code from GitHub
    - Use AWS CodePipeline to set up the continuous delivery pipeline with source, build, and deploy stages
# Prerequisites
- AWS Account with administrator-level access**
- GitHub account
- Git installed on your computer
- Recommended browser: The latest version of Chrome or Firefox
[**]Accounts created within the past 24 hours might not yet have access to the services required for this tutorial.

# Application Architecture
The diagram below provides a visual representation of the services used in this tutorial and how they are connected. This application uses GitHub, AWS Elastic Beanstalk, AWS CodeBuild, and AWS CodePipeline as pictured below.


As we go through the tutorial, we will discuss the services in detail and point to resources that will help you get up to speed with them.

# Modules
This tutorial is divided into five short modules. You must complete each module in order before moving on to the next one.
- Set Up Git Repo (5 minutes): Set up a GitHub repository to store the application code.
- Deploy Web App (10 minutes): Create the environment where the web application will be deployed using AWS Elastic Beanstalk.
- Create Build Project (5 minutes): Configure and execute the build process for the application using AWS CodeBuild.
- Create Delivery Pipeline (10 minutes): Create a pipeline to automatically build and deploy the application using AWS CodePipeline.
- Finalize Pipeline and Test (5 minutes): Add a review stage to the pipeline and test its execution.

