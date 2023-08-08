# Score Prediction ML Application

## Overview

This repository contains the code for an end-to-end machine learning application that predicts scores based on given data. The application is deployed using AWS Elastic Beanstalk and leverages AWS CodePipeline for a seamless CI/CD experience.

## Architecture

1. **Machine Learning Model**: [Description of the model, e.g., a regression model built using TensorFlow/PyTorch, etc.]
2. **AWS Elastic Beanstalk**: Used for deploying the web application.
3. **AWS CodePipeline**: Automates the build, test, and deploy phases whenever there's a change to the repository.

## Features

- **Real-time Predictions**: Users can obtain score predictions in real-time by inputting relevant data into the application.
- **Scalability**: Thanks to AWS Elastic Beanstalk, the application can automatically scale based on traffic.
- **Continuous Integration & Continuous Deployment**: Any changes to the repository trigger an automated pipeline ensuring that the latest version is always available for users.

## Prerequisites

- AWS account
- AWS CLI configured
- [Any other software/tool/library needed to run your code]

## Setup & Deployment

1. **Fork & Clone**: Fork this repository and clone it to your local machine.
2. **Configuration**: Ensure AWS CLI is set up and configured with the necessary permissions.
3. **Deployment**:
    1. Navigate to the root directory of the project.
    2. Run `eb init` to initialize the Elastic Beanstalk environment.
    3. Deploy using `eb create [environment-name]` (replace `[environment-name]` with your preferred name).
4. **CI/CD**: 
    1. Head over to AWS CodePipeline and create a new pipeline.
    2. Connect this GitHub repository as the source.
    3. Set AWS Elastic Beanstalk as the deployment environment.

 Project link: http://studentperformance-env.eba-ruhqdmug.us-east-1.elasticbeanstalk.com

