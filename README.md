# Dashboard Application

## Overview

This repository contains the source code for a Metric Dashboard Application built with HTML, JavaScript, and CSS. The deployment to a Kubernetes cluster is automated using Jenkins CI/CD pipeline.

## Technologies Used

- **HTML:** The structure of the metric dashboard.
- **JavaScript:** Logic and interactivity of the dashboard.
- **CSS:** Styling and layout of the application.
- **Kubernetes:** Container orchestration for deploying the application.
- **Jenkins:** CI/CD pipeline automation tool.

## Prerequisites

Ensure you have the following tools installed before running the CI/CD pipeline:

- Jenkins server
- Docker
- Kubernetes cluster

## Getting Started

1. **Clone this repository to your local machine:**

    ```bash
    git clone https://github.com/Frawatson/dashboard-app.git
    ```

2. **Navigate to the project directory:**

    ```bash
    cd dashboard-app
    ```

3. **Deploy Locally:**

    - Open the `index.html` file in a web browser to view the metric dashboard locally.

4. **Jenkins CI/CD Pipeline:**

    - Set up a Jenkins pipeline to automate the deployment:
    
        - Create a Jenkins pipeline job.
        - Configure the pipeline to trigger on changes to the repository.
        - Define the pipeline stages, including build and deployment steps.

5. **Kubernetes Deployment:**

    - The Jenkins pipeline include steps to deploy the application to the Kubernetes cluster, modify the deployment and service files to meet your requirement.


