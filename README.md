# CloudAppDeploy

This repository contains code for deploying a web application on Google Cloud Platform (GCP) using Packer and Terraform.

## Overview

The deployment process involves the following steps:

1. **Packer Image Creation**: Use Packer to create a custom CentOS image with necessary configurations and dependencies for deploying web applications.

2. **Terraform Infrastructure**: Use Terraform to provision the required infrastructure on GCP, including VPC, subnets, firewall rules, and VM instances.

3. **Web Application Deployment**: Deploy a sample Node.js web application on the provisioned VM instance.

## Repository Structure

The repository is organized as follows:

- `packer-image/`: Contains Packer configuration files for creating a custom CentOS image.

- `packer-image/webapp/`: Contains the source code for the sample Node.js web application.

- `tf-gcp-infra/`: Contains Terraform configuration files for provisioning GCP infrastructure.

- `severless/`: Contains serverless configuration files for deploying the web application.

## Prerequisites

Before you begin, ensure you have the following installed:

- Google Cloud Platform (GCP) Account
- Packer
- Terraform
- Node.js and npm

## Getting Started

Follow the instructions in each directory to set up the custom image, provision infrastructure, and deploy the web application.

## Contributors

Qian Chen
