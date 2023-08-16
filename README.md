# Static Website Hosting Using Amazon S3 and Terraform

Welcome to the **Static Website Hosting Using Amazon S3 and Terraform** project! This repository contains code and resources to deploy a dynamic and responsive static website using Amazon Simple Storage Service (S3) for content storage and Terraform for infrastructure provisioning.

## Project Overview

This project demonstrates the creation, configuration, and deployment of a static website on the AWS cloud using Amazon S3 and Terraform. It showcases the utilization of Infrastructure as Code (IaC) principles to automate the provisioning of resources and streamline the website deployment process.

## Features

- Automatic provisioning of AWS resources using Terraform scripts.
- Configuration of Amazon S3 bucket for static website hosting.
- Implementation of index and error documents for seamless user experience.
- Secure public access policy using Terraform-managed bucket policies.
- Responsive and engaging user interface with HTML, CSS, and JavaScript.

## Prerequisites

Before you begin, ensure you have the following:

- An AWS account with necessary permissions.
- Terraform installed on your local machine.

## Getting Started

1. Clone this repository to your local machine.
2. Navigate to the project directory:3
3. Open `terraform.tfvars` and update the variables as needed.
4. Initialize Terraform:
5. Preview the changes that will be applied:
6. Deploy the infrastructure:

## Accessing the Website

Once the infrastructure is deployed, your website will be accessible via the Amazon S3 endpoint URL. You can also configure a custom domain using Amazon Route 53 or other DNS providers.

## Cleaning Up

To avoid incurring charges, remember to destroy the created resources after you're done testing:


## Contributions

Contributions are welcome! If you find any issues or have suggestions for improvements, please feel free to create a pull request or submit an issue.


**Note:** Be cautious while working with cloud resources and infrastructure. Ensure that you understand the costs and implications of the resources you're creating and using.

For any questions or assistance, contact [Harsh Jain](mailto:Hj.harsh440@gmail.com).

