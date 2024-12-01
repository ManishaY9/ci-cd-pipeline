# CI-CD Pipeline Demo

This project demonstrates how to set up a simple **Continuous Integration (CI) and Continuous Deployment (CD)** pipeline using **Bash**, **Python**, and **Nginx**. The goal is to automatically deploy the latest code changes to a server when a new commit is pushed to a GitHub repository.

## Prerequisites

Before setting up this pipeline, ensure that you have the following installed:

- **Git**: For version control.
- **Python**: To run the commit checking script.
- **Bash**: For creating and executing deployment scripts.
- **Nginx**: To serve the website on the server.
- **Crontab**: To schedule periodic tasks.

## Setup Instructions

### 1. Create a GitHub Repository

1. Create a new repository on GitHub.
2. Clone the repository to your local machine:
   ```bash
   git clone https://github.com/ManishaY9/ci-cd-pipeline.git
